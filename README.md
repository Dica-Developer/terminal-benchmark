# terminal-benchmark

The projects aim is to provide a comprehensive set of terminal emulator tests.

Currently it is a simple bash script to measure the performance of an terminal emulator in characters per second.
Currently colour code output unicode and none unicode character output and a mix of unicode and none unicode
with a variable line length are checked.

Results:


Any feedback and help to extend the project is welcome.

Results are collected in the wiki https://github.com/Dica-Developer/terminal-benchmark/wiki/user-test-results

TODO:
* use results from repeated test executions
* add more tests that simulate editors or other CLI tools like VIM, htop, mutt, alot, ...
* test absolute postions
* test with multiplexers, e.g. tmux
* add tests for checking terminal compatibility
* calculate overall score
* ...
