I keep my home directory in git, using a detached working copy ala 
https://www.electricmonk.nl/log/2015/06/22/keep-your-home-dir-in-git-with-a-detached-working-directory/

I use an [alias](.aliases) `hgit` which sets the right git flags using an environment variable `$HOMEREPO` set in [.profile](.profile).

This is "the simplest thing that can work". If I need per-machine differences, I'll use git branches.

Previously I used @mattly's bork script to manage dotfiles. If you're looking for that it's archived under the [old-bork-master](https://github.com/edrex/dotfiles/tree/old-bork-master) branch.
