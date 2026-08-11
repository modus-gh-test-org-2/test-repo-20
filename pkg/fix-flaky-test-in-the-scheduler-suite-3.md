# Fix flaky test in the scheduler suite

Transient upstream 5xx responses now retry three times with exponential backoff and jitter.

Change #3 of 6 on branch `pr/20260811-115807-3-fix-flaky-test-in-the-scheduler-suite`.
