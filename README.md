[update-readmes]   Mode: rewrite — migrating to template structure...
# bc-wallet-mobile

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/bc-wallet-mobile)

<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/bc-wallet-mobile.git
cd bc-wallet-mobile
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration


### Google Services Files

Obtain the following Firebase/Google services files from another developer and place them in the correct locations:

```
app/android/app/google-services.json
app/ios/GoogleService-Info.plist
```

There are separate files for each build target (BC Wallet and BCSC). The files are tied to the Android package ID and iOS bundle ID respectively, so they are not interchangeable between targets. Make sure you use the files that match your `BUILD_TARGET` (in your .env).

These files are required for push notifications and other Google services but are not checked into the repository.

### Environment Variables

In the `./app/` directory copy the .env.sample `cp .env.sample .env`

```
BUILD_TARGET=<bcwallet | bcsc>
OCA_URL=<url>
MEDIATOR_URL=<url>
MEDIATOR_USE_PUSH_NOTIFICATIONS=false
PROOF_TEMPLATE_URL=<url>
REMOTE_LOGGING_URL=<url>
LOG_LEVEL=<debug | info | warn | error | fatal | trace | test>
INDY_VDR_PROXY_URL=<url>
SNOWPLOW_COLLECTOR_URL=<url>
```

Push notifications can be used locally if the mediator service has the firebase plugin and it's configured correctly.

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/bc-wallet-mobile`](https://github.com/Interested-Deving-1896/bc-wallet-mobile) and mirrored through:

```
Interested-Deving-1896/bc-wallet-mobile  ──►  OpenOS-Project-OSP/bc-wallet-mobile  ──►  OpenOS-Project-Ecosystem-OOC/bc-wallet-mobile
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
[Apache-2.0](https://github.com/Interested-Deving-1896/bc-wallet-mobile/blob/main/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
