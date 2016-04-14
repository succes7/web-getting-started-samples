# Web (Angular and Express): Image Editor UI

This is an example of using the Creative SDK for web with Angular and Express.

## How to use

Just follow the steps below.

### In your browser

1. [Register a new app for the Creative SDK](https://creativesdk.adobe.com/myapps.html)
2. Note your Client ID. You will need it soon.

### In your local development environment

1. `git clone` [the parent repo](https://github.com/CreativeSDK/web-getting-started-samples)
1. `cd` into this subdirectory
1. Run `npm install`
1. Make a new file named `apiKeys.js` in `/server` and add this code with your Creative SDK Client ID:
	
	```
	module.exports = {
		creativeSdkKey: "<YOUR_API_KEY>"
	}
	```

1. In one terminal tab, run `gulp` and leave it running
1. In a second terminal tab, run `npm start`

## Learn more

Check out the [Getting started guide](https://creativesdk.adobe.com/docs/web/#/articles/gettingstarted/index.html) for configuration options and more!