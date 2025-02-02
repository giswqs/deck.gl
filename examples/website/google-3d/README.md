This is a minimal standalone version of the Google Maps Integration example
on [deck.gl](http://deck.gl) website.

Note that this example demonstrates using deck.gl with Google Maps. For other base map options, visit the project templates in [get-started](/examples/get-started).


### Usage

To run this example, you need a [Google Maps API key](https://developers.google.com/maps/documentation/javascript/get-api-key) and a [Google Maps Map ID](https://developers.google.com/maps/documentation/javascript/webgl) for a map that is configured to use the Vector rendering mode. You can either set an environment variables:

```bash
export GoogleMapsAPIKey=<google_maps_api_key>
export GoogleMapsMapId=<google_maps_map_id>
```

Or set the `GOOGLE_MAPS_API_KEY` and `GOOGLE_MAPS_MAP_ID` variables in `app.js`.

```bash
# install dependencies
npm install
# or
yarn
# bundle and serve the app with webpack
npm start
```

### Data Source

To build your own application with deck.gl and Google Maps, check out the [documentation of @deck.gl/google-maps module](../../../docs/api-reference/google-maps/overview.md)
