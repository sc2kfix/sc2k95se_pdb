# sc2k95se_pdb

This repository contains a PDB file ("Program Database", Microsoft's proprietary debug info format) for the SIMCITY.EXE application included with the Windows 95 version of the 1996 Special Edition of SimCity 2000. It contains no executable code and no proprietary EA/Maxis intellectual property, and is generated from the sc2kfix project's internal IDA 9.x database using a plugin called FakePDB.

If placed alongside the SIMCITY.EXE application when using [https://github.com/sck2fix/sc2kfix](sc2kfix), this PDB will allow the sc2kfix exception handler to display the names for SimCity 2000 internal functions that have been reverse engineered by the sc2kfix development team instead of just printing function addresses. This allows the development team to better understand crashes and find solutions faster.
