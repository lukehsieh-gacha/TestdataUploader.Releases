# TestdataUploader.Releases

Release downloads for Testdata Uploader.

## Windows (WPF)

Download the latest Windows version from [Releases](https://github.com/lukehsieh-gacha/TestdataUploader.Releases/releases) (`wpf-v*`) or from the tool's Confluence page (company sign-in required):
https://bigasia.atlassian.net/wiki/x/BQFj-Q

- From 1.0.5 the app checks the **Confluence page** for new versions; use **Help > Check for new version...** once to sign in to Confluence. The Confluence page is where new versions appear first.
- 1.0.4 reads `latest.json` in this repository, which points it to the Confluence page.

## Windows / macOS (Electron)

Electron releases (`electron-v*`) are published on the [Releases](https://github.com/lukehsieh-gacha/TestdataUploader.Releases/releases) page of this repository.

## latest.json

The version check manifest: one entry per product (`wpf`, `electron`), each with `version`, `url` (https) and `notes`. Keep the `wpf` entry until no one uses 1.0.4 or earlier.
