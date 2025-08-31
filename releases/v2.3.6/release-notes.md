# Control Panel v2.3.6

Release Date: September 01, 2025

## What's New
- Enhanced Account-Follow feature with user-specific targeting capabilities for improved accuracy
- Advanced profile owner identification system using targeted regex patterns by user ID
- Improved multi-user Facebook page handling to prevent incorrect user detection
- Enhanced userID extraction process with optimized processing order

## Improvements
- Significantly improved page creation performance with optimized timing from 7s/5s to 4s
- Enhanced Facebook login compatibility by updating endpoint URLs to current standards
- Updated GraphQL parameters for Facebook share and reviews to ensure platform compatibility
- Improved backward compatibility through intelligent pattern fallback mechanisms

## Bug Fixes
- Resolved photo upload race condition by implementing 4-second delay before profile photo operations
- Fixed login URL inconsistencies across multiple application sections for better reliability

## Note
- This version includes important stability improvements
- Please ensure to backup your data before updating to the new version
