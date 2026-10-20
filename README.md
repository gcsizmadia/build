# Egonsoft.HU MSBuild targets

This repository contains the following files for MSBuild.

- [EgonsoftHU.Common.props](EgonsoftHU.Common.props)  
  Default build settings for EgonsoftHU nuget packages.
- [EgonsoftHU.Common.targets](EgonsoftHU.Common.targets)  
  Default build settings for EgonsoftHU nuget packages.
- [EgonsoftHU.NuGet.Common.targets](EgonsoftHU.NuGet.Common.targets)  
  Retrieves the repository URL, branch and commit so that it can be included in the .nuspec file.
- [EgonsoftHU.NuGet.NuSpecProperties.targets](EgonsoftHU.NuGet.NuSpecProperties.targets)  
  MSBuild Support for `<owners>` and `<summary>` .nuspec metadata elements. [Learn more](TARGETS_NUSPEC.md)
