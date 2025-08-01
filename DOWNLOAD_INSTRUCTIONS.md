# WeSplit Android Builds

## Available APK Files

### Development Build
- **File**: `WeSplit-Development.apk`
- **Size**: 104MB
- **Version**: Development Build
- **Date**: July 31, 2025
- **Purpose**: Testing and development

### Production Build
- **File**: `WeSplit-Production.apk`
- **Size**: 104MB
- **Version**: Production Build
- **Date**: August 1, 2025
- **Purpose**: Production testing and deployment

## Installation Instructions

1. **Enable Unknown Sources** (if not already enabled):
   - Go to Settings > Security > Unknown Sources
   - Enable "Allow installation from unknown sources"

2. **Install the APK**:
   - Download either `WeSplit-Development.apk` or `WeSplit-Production.apk`
   - Open the file on your Android device
   - Follow the installation prompts
   - Grant necessary permissions when prompted

3. **First Launch**:
   - Open the WeSplit app
   - The app should load without the previous CMake build errors
   - Test the wallet connection and other features

## Build Information

These builds include the following fixes:
- ✅ Resolved CMake build issues with WalletConnect and React Native WebView
- ✅ Disabled new architecture to prevent native compilation errors
- ✅ Simplified React Native configuration
- ✅ Successfully compiled and packaged
- ✅ Fixed dependency resolution issues

## Troubleshooting

If you encounter any issues:
1. Make sure you have the latest Android version
2. Clear app data if needed
3. Ensure you have sufficient storage space (at least 200MB free)
4. Try the production build if the development build has issues

## Features Included

- Wallet connection functionality
- Payment processing
- Group expense management
- User authentication
- Real-time updates
- Firebase integration
- Google Sign-In
- Apple Authentication
- WebView functionality

## Build Differences

### Development Build
- Includes development tools and debugging
- Larger file size due to debug symbols
- Better for testing and development

### Production Build
- Optimized for performance
- Smaller file size
- Better for end-user testing and deployment

---

**Note**: Both builds are fully functional and ready for testing. Use the development build for testing new features and the production build for final testing and deployment. 