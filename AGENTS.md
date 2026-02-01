# Contributor Guide

## Hints of develop environment

- The following folders are imported external assets and shouldn't be edited.
  - `Packages`
- The `*.cs` file may be UdonSharp. Please keep in mind the limitations of
  UdonSharp 1.0 when editing.
  - The test code in UdonSharp does not support Unity's Edit Mode; it only
    supports Play Mode. Consider this when implementing the test code.
