# Obsidian Location Plugin

![Obsidian location image generated by ChatGPT](/docs/designer.png)

Welcome to the Obsidian Location Plugin! This plugin allows you to generate location images for your Obsidian notes. You can create a map image of a specific location.

You can simply use the code block with `location` as the language identifier. If you provide then longitude and latitude, the plugin will generate a map image for that location.

## Example Usage

\```location  
Latitude: 44.64266326577057  
Longitude: -63.57530151565183  
\```

This is how it looks rendered:
![Screenshot of obsidian with rendered location image](/docs/rendered.png)

## Configuration

To make the plugin work, after installation you are required to add your Mapbox API key into the plugin settings. You can get a free API key from [Mapbox](https://www.mapbox.com/).

![Obsidian location plugin settings](/docs/settings.png)

## Full documentation

The full documentation with all options to configure your map can be found in the [DOCUMENTATION.md](./DOCUMENTATION.md) file.

## Data Privacy

This plugin uses mapbox for rendering the map image. You should be aware of the fact that it makes a call to the Mapbox API with the provided latitude and longitude. The plugin does not store any data or send it to any other server except the Mapbox API.

For more data privacy information about Mapbox, please refer to the [Mapbox Privacy Policy](https://www.mapbox.com/privacy/).

## Support

If you like the plugin and want to support the development, you can [buy me a coffee](https://buymeacoffee.com/aaronczichon.de).  
[![buy me a coffee](/docs/bmc.png)](https://buymeacoffee.com/aaronczichon.de)
