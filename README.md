# Content Delivery Network (CDN)

A Content Delivery Network (CDN) is a specialized repository designed to store and deliver Nigeria banks' logos through the Js Delivr CDN. This CDN ensures efficient and reliable distribution of static logo files.

## How to Use the CDN

To incorporate logo assets from this CDN into your project, you can utilize the following URLs:

```bash
https://cdn.jsdelivr.net/gh/wovenfinance/cdn@main/logos/<bankcode.png>
```

For instance, if you wish to include the Access Bank logo from the `logos` directory of the `main` branch, the URL would be:

```bash
https://cdn.jsdelivr.net/gh/wovenfinance/cdn@main/logos/000014.png
```

To optimize browser caching and enhance performance, it is recommended to specify a particular release tag or branch name instead of relying on the default `main` branch.

## Contributing to the CDN

Contributions to this repository are highly encouraged. If you have any static assets that you would like to share through this CDN, please follow these steps:

1. Fork the repository to your own GitHub account.
2. Create a new branch with a descriptive name for your asset.
3. Add your static asset to the appropriate directory within the repository.
4. Submit a pull request to the `main` branch of this repository.
5. Your pull request will undergo review, and if accepted, your asset will be merged into the CDN.

Please ensure that your contributions adhere to the guidelines and best practices set forth by this repository. Additionally, it is essential to consider any licensing restrictions or copyright issues associated with the assets you contribute.

## Issues and Support

If you come across any problems or have inquiries regarding this CDN, feel free to open an issue on the GitHub repository. The maintainers of this project will make their best efforts to assist you promptly.

## License

This repository is licensed under the [MIT License](LICENSE). By contributing to this repository, you agree to distribute your contributions under the same license.