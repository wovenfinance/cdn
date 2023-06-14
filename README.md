# CDN (Content Delivery Network)

CDN is a repository created to store and serve static assets through the Js Delivr CDN. This allows for fast and reliable delivery of static files.

## How to Use

To include assets from this CDN in your project, you can use the following URLs:

```
https://cdn.jsdelivr.net/gh/<your-username>/cdn@<release-tag>/<path-to-asset>
```

Replace `<your-username>` with your GitHub username and `<release-tag>` with the desired release tag or branch name. `<path-to-asset>` should be the relative path to the asset file you wish to include.

For example, if you want to include a JavaScript file named `script.js` from the `scripts` directory of the `main` branch, the URL would be:

```
https://cdn.jsdelivr.net/gh/wovenfinance/cdn@main/logos/bankname.png
```

To ensure browser caching and improve performance, it is recommended to use a specific release tag or branch name instead of the default `main` branch.

## Contributing

Contributions to this repository are welcome. If you have any static assets that you would like to share through this CDN, follow these steps:
