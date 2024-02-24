# Hibiki Duwuca Linux System Package Manager (duca) main repository
A repository for duca package manager

HOW IT WORKS:
1. "duca" will use this github repos as default repository for hibiki duwuca linux system
2. One folder call "packages" contains a lot of package uploaded by me or someone else. For example: in packages folder, there is a package call foo. To install foo package, type: duca -i foo)
3. Then it extract the package and run package script and installer script (instscr) (it also contain reinstall and uninstall function)

Explanation:
* pckzip: package zip contain package script (main.dupck)
* dupck: Duca Packager Script

And everyone CAN upload their package into this repos and use it in that package manager.
