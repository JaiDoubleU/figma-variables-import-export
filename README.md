# Figma Variable Importer / Exporter

Figma Variable Importer / Exporter is a FREE open source Figma plugin that allows you to import and export variables from/to Figma. Using a JSON file, you can import variables to Figma and export them back to JSON. It supports all variable types (as of 05/06/2024). You can use it to import/export variables with your existing variables and collections!

The plugin is not yet available for the Figma community, but you are able to clone and build this plugin yourself.

## Note

Please note that this plugin does support multiple modes for each collection. Multiple modes is a paid feature in Figma. I have not tested this plugin when using a Figma account that does not have multiple modes. I will add error handling for this in the future.

## Installation

1. Clone this repository
2. Run `npm install`
3. Run `npm run build`
4. Open Figma
5. Go to `Plugins` -> `Development` -> `New Plugin...`
6. Click on `Click to choose a manifest.json file`
7. Select the `manifest.json` file in the root of this repository
8. Click on `Create new plugin`
9. You should now see the plugin in the plugins menu

## Usage

Please see the [How To Use](doc/HowToUse.md) document for information on how to use this plugin.

## Credits

The style of the plugin was inspired by [Figma Variables To JSON](https://www.figma.com/community/plugin/1345399750040406570/figma-variables-to-json).

The logo was from Figma's variable icon.

## License

Please see LICENSE for the license of this software.

