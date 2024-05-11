# Dev Notes For Contributors
This file may be used by contributors to track technical notes for updates to inner workings, but probably won't be interesting to end users.
Please add notes that will help future contributors.

## Version 1.24

- Notes from [Nathan Shulman](https://github.com/nshulman)
    - Cleaned up all ES Lint Errors
    - Added more progress status and error details to Test Framework page
    - Updated instructions for Firefox and Chrome build prior to testing and to reflect new Firefox UI - manifest in the addon folder is sufficient
    - Due to an error from React mentioning that input value may not be null, nullToEmptyString() helper function was added to prevent nulls as value
    - To add a tooltip to an option (in options.js) add the property `tooltip: "Text"` to any option in the array
    - Updated SVG file to latest SLDS version, so you'll be able to use the [newest icons](https://www.lightningdesignsystem.com/icons/).  Initial use case was need for `toggle_panel_right` and `toggle_panel_bottom` in a future release, but they were not in the current SVG