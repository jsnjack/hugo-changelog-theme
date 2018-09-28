Hugo Changelog Theme
=====

A [Hugo](https://gohugo.io/) theme to display changelog

# Features
 - Build with [Spectre.css](https://picturepan2.github.io/spectre/) (All unused components are disabled)
 - Pagination
 - Mobile friendly

# Conventions
 - Create non-released entries in `experimental` folder. All of them are displayed in the top of the first page
 - Create released entries in `released` folders. Entries are sorted by Weight. Weight is displayed as version

# Shortcodes
 - `{{% tag fixed %}}` - create a specific tag before entry text. Available tag types are: added, changed, fixed, deprecated, removed, security

# Settings
```
[params]
    customCSS = ["css/styles.css"]  # List of css files to include on the website. Reltive to the static/ folder
    disableOriginalStyles = true  # Do not include original CSS styles
```

# Development
## Serve example website
```bash
cd exampleSite && hugo serve --theme hugo-changelog-theme --themesDir ../../
```
