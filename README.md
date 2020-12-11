# CART_Model
OpenFAST model of NREL's Controls Advanced Research Turbine (CART)

The OpenFAST model is compatible with the latest release of [OpenFAST](https://github.com/OpenFAST/openfast) (2.4.0 as of Dec. 11, 2020).  The FAST8 model is not currently supported or tested.

The provided control input (`OpenFAST/CART_DISCON.IN`) is designed to work with the latest release of [ROSCO](https://github.com/NREL/ROSCO).  The user will need to upate `DLL_FileName` in `OpenFAST/CART3_ServoDyn.dat` to point to their own compiled dynamic library.
