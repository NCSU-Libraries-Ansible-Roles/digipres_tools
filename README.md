# digipres_tools

Installs (mostly via Homebrew) packages used during born-digital processing

## Prequisites

The following roles should be invoked in an Ansible playbook before this one to ensure that dependencies are installed:

* basic_setup: https://github.com/NCSU-Libraries-Ansible-Roles/basic-setup
* homebrew: https://github.com/NCSU-Libraries-Ansible-Roles/homebrew

## Variables

The only variable available is `homebrew_user`. The default value is `deploy`. For Vagrant provisioning, use `vagrant`. Use other values as needed for other situations.


## Packages/repos installed

### via yum

* tar

### via brew_tap

* homebrew/bundle
* homebrew/core
* richardlehane/digipres

### via homebrew

* afflib
* antiword
* bulk_extractor
* cdparanoia
* clamav
* coreutils
* ddrescue
* disktype
* duff
* fdupes
* findutils
* libarchive
* libewf
* sleuthkit
* tree
* twarc
* richardlehane/digipres/siegfried
