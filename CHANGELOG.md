# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [1.2.0 - 2024-04-04]
### Added
- New workflow for Rust builds
### Changed
- New variable push-to for docker-ci
## [1.1.3 - 2022-05-20]
### Fixed
- Moved docker-ci-template.properties.json to the workflow-templates directory
## [1.1.2 - 2022-05-20]
### Fixed
- Moved Secrets Section in Docker CI Template to the build job
## [1.1.1 - 2022-05-20]
### Fixed
- Merged Fixes regarding the syntax of the Java CI Template
## [1.1.0 - 2022-05-20]
### Added
- Added a template for Building Docker Images
## [1.0.2 - 2021-12-21]
### Fixed
- Moved workflow-templates directory to project root. This should make the template defined there visible
## [1.0.1 - 2021-12-21]
### Added
- Metadata for "Java Library CI Workflow Template". With this, it should be useable.
### Fixed
- Corrected call for the maven workflow in Java Library CI Workflow Template
## [1.0.0 - 2021-12-21]
### Added
- Workflow Template for automatically building, testing and pushing a java library to [https://oss.sonatype.org](https://oss.sonatype.org)
