# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

# v0.0.2 2016-07-25

### Fixed

* Don’t return the default key bindings if we’re not handling the event. Returning it stops any other plugins halts the callback chain, and so stops any other plugins from being able to insert behaviour.

# v0.0.1 2016-04-21

First public release
