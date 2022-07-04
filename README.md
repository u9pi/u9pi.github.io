# u9pi.github.io

I welcome the pioneer and hope to develop further.

# Update Status

## 1.4 ([raw](https://pkg.owop.xyz/moonless/moonl.x14.js))

- Decided to disable the SVT for a long time.
- Fixed some errors.

## 1.3 ([raw](https://pkg.owop.xyz/moonless/moonl.x13.js))

- Page loads slightly faster.
- Access via the web address is stable and usually error-free.
- In the **loader**, the script related to app mount has been modified.
- The **framework** also changed the rules for style map.

## 1.2 ([raw](https://pkg.owop.xyz/moonless/moonl.x12.js))

- Access is possible through the address bar.
- About windows no longer go through the roof when scrolling.

## 1.1.3211349 ([raw](https://pkg.owop.xyz/moonless/integrated/moonl.x11_3211349.js))

- Fixed an issue where you were trying to check for marked rather than markdown-it.

## 1.1.321644 ([raw](https://pkg.owop.xyz/moonless/integrated/moonl.x11_321644.js))

- Changed the markdown parser.
- Images in light/dark mode are applied according to the browser theme.

## 1.1 ([raw](https://pkg.owop.xyz/moonless/integrated/moonl.x11.js))

- Removed shadow effect because it smears on mobile device.
- Now depending on the browser language the page language will also change.[^lang]
- Turned off 'Recently Viewed', which unable to use yet.

## 1.0 ([raw](https://pkg.owop.xyz/moonless/integrated/moonl.x10.js))

### Moonless-Loader 1.1.316

- The Moonless-Loader loads the framework and renders it.
- **Configuration**:
  - version: Returns the version of the current loader as a string value.
  - loader(): Export the framework as a callback.
  - lslc(): means 'loader successfully load completely' and renders the mapping coming in from the callback.

### Moonless-Framework 0.1

- **Configuration**:
  - __version: Returns the version of the current framework as a string value.
  - init(): The framework dynamically adds the components for it to work.[^warn-loader]

[^lang]: It will be stored in the **`u9pi/u9pi.github.io/language`** directory for future updates.
[^warn-loader]: But without the loader the work will be cancelled
