# plugin-build-tests

This repository is for testing includes and plugins across the SA:MP community.

It runs as a TravisCI cron-job and includes all major plugins as dependencies to
ensure any sampctl regressions are caught.

This would be included in the sampctl unit tests but it takes quite a while to
run and uses up lots of GitHub API calls.
