# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-03-09

### Added

- Initial release
- PostgreSQL deployment on Proxmox with RDS-like interface
- Support for PostgreSQL versions 14, 15, 16, 17
- RDS-like instance classes (db.t3.small - db.t3.2xlarge)
- Automatic PostgreSQL tuning based on instance size
- Cloud-init based installation and configuration
- Database user and initial database creation
- CIDR-based access control
- Static IP and network configuration
- SSH key authentication
- Tag support
