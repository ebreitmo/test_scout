# test_scout
Chapter4

Lecturer uses github codespace to use terminal to run e.g. ```make test-script```

Requires python code files in the main directory for tests to run on. The files
- Dockerfile
- Makefile
- entrypoint.sh
- action.yml

are 'not enough'. But the action will run and report back that no python files were found (action run 2025-10-31).
There are also no ```test_*.py``` files.

About [github actions cheatsheet & custom action inputs](https://www.glukhov.org/post/2025/07/github-actions-cheatsheet/#defining-custom-action-inputs).
