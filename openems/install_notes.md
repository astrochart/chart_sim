# Loose notes on installation

## Running on a Mac
Following instructions here:
https://docs.openems.de/en/latest/install/clone-build-install.html

I downloaded the openEMS repo.
Had to run install_deps.sh:
$ ./scripts/install_deps.sh --install --python
  (this took a while... like a WHILE)
  It used homebrew, which luckily I already had installed. Probably needs to be installed if not.
then:
$ ./update_openEMS.sh ~/opt/openEMS --python

I put the openEMS path (export PATH="$HOME/opt/openEMS/bin:$PATH") in the activate file
$HOME/opt/openEMS/venv/bin/activate

then activate it.
source $HOME/opt/openEMS/venv/bin/activate

The linked instructions above then have a couple commands to try out to be sure everything worked.