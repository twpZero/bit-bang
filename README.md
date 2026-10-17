# bit-bang
Bit-Bang is an educational program for IT Security reconversion

**Website:** https://bit-bang.org/

## Contents

* `index.html`, `labs/`, `resources.html`, `credits.html`: the lab website (one page per lab).
* `setup_vm.sh` and `vm-assets/`: prepare an Ubuntu 22.04 / Debian 12 VM for the labs.
* `Common/`: the original exercises (`beginnerPack/`) and the `break.sh` / `fix.sh` / `prequisite.sh` templates.

## Set up a lab VM

```bash
sudo bash setup_vm.sh              # install all labs
sudo bash setup_vm.sh --lab aes    # install one lab
sudo bash setup_vm.sh --list       # list the labs
sudo bash setup_vm.sh --reset      # reset all labs to their initial state
```
