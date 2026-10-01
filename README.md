# GS13 config repository

On the live server these files replace any files of the same name within the config/ subfolder of the repo. This is necessary because testing on localhost necessarily requires different configs than the live servers. To facilitate this this repo is pulled into GameStaticFiles/config/ by TGS whenever dreamdaemon starts (via a helper EventScript).

Feel free to make PRs to adjust the configs here, but bear in mind that they may not be accepted.

If you need to add a new config file ideally make a commit with the base config file copied over from the repo & then commit your changes on top of that.