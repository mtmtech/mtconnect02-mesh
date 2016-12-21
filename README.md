# MtConnect02 Mesh

## Based on CSRmesh SDK 1.3
Following patch file is based on CSRmesh SDK 1.3. Download the source from CSR support site. It require an account of CSR support with granted access.
https://www.csrsupport.com/document.php?did=55946 Then you can use Git patch function or GNU patch utility to apply.

## MtSense01.patch
### Git patch
```Bash
cd CSRmesh-1.3-Examples-Applications_icp
git am MtSense01.patch
```
### GNU patch
```Bash
cd CSRmesh-1.3-Examples-Applications_icp
patch -p1 < MtSense01.patch
```
