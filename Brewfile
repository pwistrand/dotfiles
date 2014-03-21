# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
install coreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, g-prefixed
install findutils
# Install Bash 4
install bash

# Install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
install vim --override-system-vi
tap homebrew/dupes
install homebrew/dupes/grep
tap josegonzalez/homebrew-php

# This formula didn’t work well last time I tried it:
#install homebrew/dupes/screen

# Install generic development
install git
install tig
install tree
install autojump
install htop-osx

# Install languages and environments
install python
install node
install erlang

# rbenv ruby environment manager and ruby-build plugin
install rbenv
install ruby-build

# Install build tools
install maven
install sbt

# Install stack components
install nginx --with-gunzip

install mongodb

install rabbitmq

# Install general utilities
install webkit2png
install graphviz

install jq

tap homebrew/versions

# Remove outdated versions from the cellar
cleanup
