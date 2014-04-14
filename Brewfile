#!/bin/bash

# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# Install GNU core utilities (those that come with OS X are outdated)
install coreutils
echo "Don’t forget to add $(brew --prefix coreutils)/libexec/gnubin to \$PATH."
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, g-prefixed
install findutils
# Install Bash 4
install bash

# Install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
tap homebrew/dupes
install homebrew/dupes/grep
# brew tap josegonzalez/homebrew-php

# Install everything else
install ack
install git
install node
install rename
install tree


tap homebrew/versions
install lua52


# Remove outdated versions from the cellar
cleanup
