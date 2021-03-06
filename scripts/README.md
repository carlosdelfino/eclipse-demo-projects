# Helper scripts

These scripts were created on macOS, and the ones suffixed with `.command` are specific to macOS; the `.sh` scripts should also be fine on GNU/Linux, Windows MSYS2, and on the new [Windows Subsystem for Linux](https://msdn.microsoft.com/commandline/wsl/about).

For those who insist on native Windows, separate PowerShell scripts would be required, but considering Microsoft's move towards Linux, this would probably not be worth the effort. Anyway, if you manage to create them, please consider improving your karma and contribute them back to the community.

## update-xpacks-repo.sh

The xPacks are stored as separate folders in `$HOME/.xpacks`. For now, the format is the original Git, but separate versions will be added as the XCDL tool will be available.

During the first run, the `xpack` branch is cloned into the local folder.

Subsequent runs will pull the latest commit from the current branch.

If, for one reason or another, it is necessary to stick with one older commit for a specific repository, after the initial clone, comment it out to avoid further updates.

## update-xpacks-repo.command

Wrapper for macOS; execute it by double clicking in Finder.
