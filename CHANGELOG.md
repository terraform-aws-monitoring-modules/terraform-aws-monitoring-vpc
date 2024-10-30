# Changelog

## [1.0.0] - 2024-10-28

### Added
- Initial release of the VPC Monitoring module.
- Support for monitoring Virtual Private Clouds (VPCs) with custom metric filters and alarms.
- Configurable parameters for VPC IDs, event names, and CloudWatch log settings.
- Automatic creation of CloudWatch metric filters based on specified VPCs and their respective events.
- Alarms triggered based on defined thresholds for the specified metrics.
- Detailed variable descriptions for easy customization and configuration.

### Changed
- Updated Terraform examples in [`README.md`](README.md) to reference the module source from the Terraform Registry.
