# Changelog
Changelog format: [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
Version scheme: [Semantic Versioning](https://semver.org/spec/v2.0.0.html)
Versioning is handled by GitVersion, if there is anything to build

## [Unreleased]
### Added
- Default solution properties
	* Metadata
	* Famework
	* Build configuration
- Versioning with GitVersion
- Overridable with solution-level Common.Solution.[props|targets] files
- Common tasks
	* ILRepack based linker
		* enable with ILRepackLink=true
	* Zip and ZipDir tasks
		* Lifted from: https://github.com/moozzyk/MSBuild-Tasks
		* Update to use RoslynCodeTaskFactory
		* Add CompressionLevel property

[Unreleased]: https://github.com/AndASM/AndASM-MSBuild-Extensions
[0.1.0]: https://github.com/AndASM/AndASM-MSBuild-Extensions/releases/v0.1.0
