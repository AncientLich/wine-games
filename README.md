# wine-games

This is a set of bash and python3 scripts (MIT licensed) 
that will build wine from source 
managing different wine versions

## usage
copy the file in this repository in HOME/wine-games
the system will work only if it stay in that exact location.

Currently the system supports only two scripts:
   
   * wine-update -> update the system. Download git wine and wine staging sources and update the list of the versions available (versions.txt will be created)
   * wine-build -> build a specific version of wine. For example: wine-build 2.21 --std --64 will build wine-2.21 but only standard (not staging) version and only 32 bit.
   
python scripts and .patch file are used by those two scripts internally.