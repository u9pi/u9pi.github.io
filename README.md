# u9pi.github.io

<a href="https://github.com/u9pi/u9pi#gh-light-mode-only"><img width="46%" src="https://pkg.owop.xyz/pioneer/ql.png"></a>
<a href="https://github.com/u9pi/u9pi#gh-dark-mode-only"><img width="46%" src="https://pkg.owop.xyz/pioneer/x0.png"></a>

I welcome the pioneer and hope to develop further.

## Version 1.1 ([raw](https://pkg.owop.xyz/moonless/moonl.x11.js))

- Removed shadow effect because it smears on mobile device.
- Now depending on the browser language the page language will also change.[^1]
- Turned off 'Recently Viewed', which unable to use yet.

## Version 1.0 ([raw](https://pkg.owop.xyz/moonless/moonl.x10.js))

### Moonless-Loader 1.1.316

- The Moonless-Loader loads the framework and renders it.
- **Configuration**:
  - version: Returns the version of the current loader as a string value.
  - loader(): Export the framework as a callback.
  - lslc(): means 'loader successfully load completely' and renders the mapping coming in from the callback.

### Moonless-Framework 0.1

- **Configuration**:
  - __version: Returns the version of the current framework as a string value.
  - init(): The framework dynamically adds the components for it to work.[^2]

[^1]: It will be stored in the **`u9pi/u9pi.github.io/language`** directory for future updates.
[^2]: But without the loader the work will be cancelled
