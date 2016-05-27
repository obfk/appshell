# App Shell

https://developers.google.com/web/fundamentals/getting-started/your-first-progressive-web-app/?hl=en

>EC: replace localstorage with [https://www.npmjs.com/package/idb](idb)

## Notes

>Features provided via service workers should be considered a progressive enhancement, and added only if supported by the browser. For example, with service workers you can cache the app shell and data for your app, so that it’s available even when the network isn’t. When service workers aren’t supported, the offline code isn’t called, and the user gets a basic experience. Using feature detection to provide progressive enhancement has little overhead and it won’t break in older browsers that don’t support that feature.
