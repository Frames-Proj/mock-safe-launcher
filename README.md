# Building

To build the launcher yourself, this
repo also contains a script called `build.bash` which will build
the versions of the launcher and client libs pinned in this repo.
In order to use the script, you have to make sure you have downloaded
the submodules. You can do this when you first clone the repo by
doing

    git clone --recursive -j8 git@github.com:wgallo3/MockRoutingPack.git

or if you have already donwloaded the repo and want to just fetch the
submodule content, you can do

    git submodule update --init --recursive

Then you can just type `./build.bash`. The script will prompt to you
to install the right version of rust and node.
