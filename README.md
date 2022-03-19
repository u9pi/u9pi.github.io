# u9pi.github.io

![_`Nice to meet you, pioneer.`_](https://pkg.owop.xyz/moonless/pioneer.jpg)

I welcome the pioneer and hope to develop further.

## Version 1.0 ([raw](https://pkg.owop.xyz/moonless/moonl.js))

### Moonless-Loader 1.1.316

- The Moonless-Loader loads the framework and renders it.
- **Configuration**:
  - version: Returns the version of the current loader as a string value.
  - loader(): Export the framework as a callback.
  - lslc(): means 'loader successfully load completely' and renders the mapping coming in from the callback.

### Moonless-Framework 0.1

- **Configuration**:
  - __version: Returns the version of the current framework as a string value.
  - init(): The framework dynamically adds the components for it to work.
            <br> _`But without the loader the work will be cancelled`_
