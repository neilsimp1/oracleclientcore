# OracleClientCore
## Unofficial oracle client for .net core. Based on mono's oracle client.

- Update on 04/23/2017: Converted solution/project to Visual Studio 2017. Added compiler defines for a platform to the oci library.
- Update on 09/11/2018: Updated to run on .NetStandard2.0 and updated all dependencies to their latest versions.


OCI_WINDOWS is "oci" which is oci.dll
OCI_LINUX is "libclntsh.so"
OCI_MACOS is "libclntsh.dynlib". not sure about Mac OS.

In OciDefines.cs, just define one of the above like:
#define OCI_WINDOWS
