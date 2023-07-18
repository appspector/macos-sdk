[![GitHub release](https://img.shields.io/github/release/appspector/macos-beta.svg)](https://github.com/appspector/macos-beta)
[![Build Status](https://app.bitrise.io/app/17e138eab39135f1/status.svg?token=jlmNh2tlt2SQojwlhMojNw)](https://app.bitrise.io/app/17e138eab39135f1)
# ![AppSpector](https://github.com/appspector/macos-beta/raw/master/github-cover.png)

Debugging don't have to be painful!

Welcome to the AppSpector macOS closed beta program.
We invited you here to share a new version of the SDK, and get you feedback and thoughts on it.
SDK updates will be available here under the [releases](https://github.com/appspector/macos-beta/releases/latest) section same as in public repo.
Please note that only XCFramework build is available for now, no package managers. It's a fat binary, arm64/x86_64.


* [Installation](#installation)
* [Known Issues](#known_issues)
* [Feedback](#feedback)


## Installation
Only manual installation is supported for now.
- Download SDK binary from the [releases](https://github.com/appspector/macos-beta/releases) section in this repo
- Drag AppSpectorOSXSDK.xcframework to your xcode project window and select 'Copy items if needed'
# ![AppSpector](https://github.com/appspector/macos-beta/raw/master/install-1.png)
- Switch framework embed type to 'embed and sign'
# ![AppSpector](https://github.com/appspector/macos-beta/raw/master/install-2.png)
- Import SDK: `import AppSpectorOSXSDK`
- To configure and run SDK please refer to the [iOS docs](https://docs.appspector.com/docs/ios-sdk)


## Known Issues
- FS, Screenshot and SQLite monitors doesnt work. Switching to them could drop a session or even crash your app. Will be fixed in the nearest update.
- Env monitor shows zeroes in FPS and battery sections
- App icon update does not work
- NC monitor system notifications filtering doesn't work properly

## Feedback
If you have any questions, suggestions or issue reports you can ping us in [Slack](https://slack.appspector.com/) or drop us a line: [info@appspector.com](mailto:info@appspector.com)
Please don't discuss macOS build related topics publicly as macOS SDK beta is available for the small part of users. Use DM in slack or email/HubSpot with AppSpector engineers.
You can also use this repo on GitHub to file an issue or ask a question, but remember it will be available for everyone invited to private beta testing program.
