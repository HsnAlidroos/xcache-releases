# Xcache

Find and safely clean developer caches on macOS — Xcode, simulators, package managers, and more.

## Download

Get the latest `.dmg` from [Releases](../../releases). Builds are signed with a Developer ID and notarized by Apple.

## Install · التثبيت

Requires macOS 14 or later · يحتاج macOS 14 أو أحدث

**From the browser · من المتصفح:** download the `.dmg` from Releases, open it, and drag Xcache into Applications.
حمّل ملف `Xcache-1.7.3-meta.dmg` من صفحة Releases، افتحه، واسحب Xcache إلى مجلد Applications.

**From Terminal · من الـ Terminal:**
```bash
curl -L -o ~/Downloads/Xcache.dmg https://github.com/HsnAlidroos/xcache-releases/releases/download/v1.7.3/Xcache-1.7.3-meta.dmg
hdiutil attach ~/Downloads/Xcache.dmg -nobrowse -mountpoint /Volumes/Xcache
cp -R /Volumes/Xcache/Xcache.app /Applications/
hdiutil detach /Volumes/Xcache
open /Applications/Xcache.app
```

Developed by [hsnalidroos.dev](https://hsnalidroos.dev).
