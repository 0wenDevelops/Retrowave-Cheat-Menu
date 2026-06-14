# Release Checklist

Use this checklist before publishing a new public build.

## Build

- [ ] Update the project version number.
- [ ] Build the release DLL.
- [ ] Confirm the file name matches the release version.
- [ ] Remove temporary debug files that should not ship.

## Test

- [ ] Launch the game with the release build.
- [ ] Confirm the menu opens with the documented hotkey.
- [ ] Test the main menu tabs.
- [ ] Check logs for obvious errors.
- [ ] Verify the supported loader version.
- [ ] Test using a backed-up save.

## Package

- [ ] Include the compiled DLL.
- [ ] Include source archive if publishing source with the release.
- [ ] Include release notes.
- [ ] Confirm installation instructions are still accurate.

## Publish

- [ ] Create a GitHub Release.
- [ ] Use a version tag such as `v3.0.1`.
- [ ] Upload release assets.
- [ ] Add clear release notes.
- [ ] Confirm the README download link works.

## After release

- [ ] Download the public asset and test it.
- [ ] Check that screenshots still match the current UI.
- [ ] Update README version badges if needed.
