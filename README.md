iOS images export script illustrator
===============

An Adobe Illustrator script for easily exporting your artboards to iOS images assets with the correct directory structure and resolutions.

Both app icons and standard images can be exported easily. App icons are exported in the resolutions required by Apple for iPhone, iPad, Spotlight icon, etc. Normal images are exported with a scale factor.

Usage
---
1. Import the script into Adobe Illustrator (to make the script appear under the scripts menu). To import the script save both `export_assets_for_iOS.jsx` and `json2.js` scripts into the `/Adobe Illustrator CC 2014/Presets/{localization}/Scripts/` folder. Restart Adobe Illustrator for the changes to have effect!
2. Open the Illustrator file that includes the artboards you want to export.
3. Select the script from the scripts menu: `File > Scripts`
4. Choose the directory where the images should be exported to. This script is designed to fully integrate with the Xcode IDE, so the correct directory would be `Images.xcassets` folder in your Xcode project.
5. Choose which artboards you want to export as app icons and which as image assets.

![overview](https://cloud.githubusercontent.com/assets/5703745/7371387/d7792af4-edc0-11e4-8fec-1f2277314460.png)

Features
---
* The script supports both image sets as app icons.
* For images the corresponding `.imageset` folder is created. For app icons the corresponding `.appiconset` folder is created.
* In each folder the `Contents.json` file is created that describes the resources. This way the resources are correctly displayed in Xcode.

License
---
This repository is under the MIT license, have a look at the `LICENSE` file.