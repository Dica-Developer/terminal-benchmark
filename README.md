# terminal-benchmark

The projects aim is to provide a comprehensive set of terminal emulator tests.

Currently it is a simple bash script to measure the performance of an terminal emulator in characters per second.
Currently colour code output unicode and none unicode character output and a mix of unicode and none unicode
with a variable line length are checked.

Results:

On laptop with Intel(R) Core(TM) i7-4558U CPU @ 2.80GHz

Alacritty + tmux
2310021 coloured characters per second
1469603 unicode characters per second
4741729 none-unicode characters per second
 680047 Mixed characters per second

Alacritty
4231845 coloured characters per second
5913143 unicode characters per second
9526407 none-unicode characters per second
 949401 Mixed characters per second

Any feedback and help to extend the project is welcome.

TODO:
* use results from repeted test executions
* add more tests that simulate editors or other CLI tools like VIM, htop, mutt, alot, ...
* test absolute postions
* test with multiplexers, e.g. tmux
* create page for collecting test results
* add tests for checking terminal compatibility
* calculate overall score
* ...
