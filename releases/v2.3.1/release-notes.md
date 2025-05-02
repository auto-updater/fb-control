# Control Panel v2.3.1

Release Date: May 02, 2025

## What's New
- Parallelized hardware identifier collection for improved performance
- Implemented ThreadPoolExecutor with 5 worker threads for hardware checks
- Refactored component collection into isolated functions for better maintainability

## Bug Fixes
- Extended hardware identification timeout from 10s to 60s for low-resource devices
- Updated GraphQL relay providers to match latest Facebook API specifications
- Updated page review and post share functions for Facebook GraphQL compatibility

## Note
- This version includes important stability improvements
- Please ensure to backup your data before updating to the new version
- This update focuses on performance improvements and bug fixes related to hardware identification