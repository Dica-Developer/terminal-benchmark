# terminal-benchmark

This project's aim is to provide a comprehensive set of terminal emulator tests.

Currently, it is a simple bash script which measures the performance of a terminal emulator in characters per second. It runs tests with:
- color code unicode characters
- the none unicode character
- a mix of unicode and none characters

> if you are running on osx, you'll need to install coreutils **brew install coreutils**

Any feedback and help to extend the project is welcome.

Results are collected in the wiki: https://github.com/Dica-Developer/terminal-benchmark/wiki/user-test-results

TODO:
* use results from repeated test executions
* add more tests that simulate editors or other CLI tools like VIM, htop, mutt, alot, ...
* test absolute postions
* test with multiplexers, e.g. tmux
* add tests for checking terminal compatibility
* calculate overall score
* ...
