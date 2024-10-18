# <img src="https://cdn.jsdelivr.net/gh/chocolatey-community/chocolatey-packages@d8a28da83b3b9bf058e1fbbeed5ce74329b73245/icons/vcredist2017.png" width="48" height="48"/> [Microsoft Visual C++ Redistributable for Visual Studio 2017](https://chocolatey.org/packages/vcredist2017)

Microsoft Visual C++ Redistributable for Visual Studio 2017 installs run-time components of Visual C++ libraries. These components are required to run C++ applications that are developed using Visual Studio 2017 and link dynamically to Visual C++ libraries. The packages can be used to run such applications on a computer even if it does not have Visual Studio 2017 installed. These packages also install run-time components of C Runtime (CRT), Standard C++, MFC, C++ AMP, and OpenMP libraries.

This package is only a metapackage which points to the latest Visual C++ Redistributable version released in the Visual Studio 2017 release channel. The actual installation of the runtime is performed by the [vcredist140](https://chocolatey.org/packages/vcredist140) package.

## Notes

[Supported Operating Systems](https://www.visualstudio.com/en-us/productinfo/vs2017-system-requirements-vs): Windows 10, Windows 8.1 / Server 2012 R2 (with KB2919355), Windows 8 / Windows Server 2012, Windows 7 SP1 (with KB3033929) / Server 2008 R2 SP1, Windows Vista SP2 / Server 2008 SP2, Windows XP SP3 / Windows Server 2003 SP2
