# deprecated - ember-simple-google-maps

This addon was used for teaching older versions of Ember (before v3.14), and is deprecated.
This means it will no longer accept PRs and updates, however you can still install this addon from npm
if you are learning older versions of Ember.

To view the current supported official Ember tutorial, visit
[https://guides.emberjs.com/release/tutorial/part-1/](https://guides.emberjs.com/release/tutorial/part-1/).

Makes the Google Maps API available to a consuming application by supplying its external script to the Application's `index.html`.

Once the application starts, the user may interact with the Google maps API [as documented](https://developers.google.com/maps/documentation/javascript/tutorial).

## Customization

Aspects of the Google Maps Installation can be customized, by supplying environment variables to the server process.

* `GOOGLE_MAPS_URL` - The URL to the API script.  Defaults to `https://maps.googleapis.com/maps/api/js`.
* `GOOGLE_MAPS_VERSION` - The version of the API script. Defaults to `3.22`.
* `GOOGLE_MAPS_API_KEY` - The Google Maps API Key.  Defaults to none, which is OK when running your server on localhost, but will require a key when deploying to a remote server.

## Installation

* `git clone <repository-url>` this repository
* `cd ember-simple-google-maps`
* `npm install`

## Running

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).

## Running Tests

* `npm test` (Runs `ember try:each` to test your addon against multiple Ember versions)
* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [https://ember-cli.com/](https://ember-cli.com/).
