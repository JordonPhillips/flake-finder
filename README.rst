flake-finder
============

Integration tests depend on external state, so sometimes they can be flaky if
there is some situation that isn't being accounted for. The purpose of this
script is to repeatedly run tests over and over in mulitple processes, waiting
for failures. Logs for failed test runs are kept, logs for successful runs are
discarded.
