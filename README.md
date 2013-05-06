# =rush=

Simple Ruby Shell.

## Supported Features

* Path Completion
* History
* Sourcing
* Aliasing

## Installation

Currently development is only tested on Mac and Linux, with versions of ruby 1.8.7 or greater. Since the default version of mac is 1.8.7 this is my main target. It's easy however to use for your own development newer versions of ruby. I for example have added the following to my `.rush_rc`

    # make /usr/local/bin overide anything in all other paths.
    ENV['PATH'] = '/usr/local/bin:' + ENV['PATH']
