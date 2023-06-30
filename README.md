# pldoh
Perl client for DoH

## Installation & requirements: 

* install (copy) the `pldoh` file into a new, empty directory (e.g. `~/pldoh/`)
* make it executable: `chmod a+x pldoh` 
* needs [Leap](https://github.com/antelopeio/leap/releases/latest): `cleos` and `keosd` executables in the current directory (can be manually extracted from inside the Leap .deb release) or Leap deb installed in the system
* needs Perl 5+ (comes with Ubuntu 22)
* needs Curses module for Perl installed in the system (may need to use cpan to install)

## Wallet & security:

`pldoh` creates a new, empty `default.wallet` file in its directory. This wallet is exclusively for interacting with `pldoh`. You have to import any keys you want to use with `pldoh` into that wallet. `pldoh` will help you do that.

It's a good security practice to create an account with only the bare minimum resources required to play.

## Help:

`pldoh -h`

## Run in interactive mode:

`pldoh`
