# Contributor Guide

## Hints of develop environment

- In the `Assets` directory, only the `Assets/black.kit` directory is a
  proprietary implementation.
  Normally, no changes are made except in this folder.
- The other folders are external assets, so changes should be minimal.
- The `*.cs` file may be UdonSharp. Please keep in mind the limitations of
  UdonSharp 1.0 when editing.
  - The test code in UdonSharp does not support Unity's Edit Mode; it only
    supports Play Mode. Consider this when implementing the test code.
