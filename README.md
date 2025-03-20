# Numa Docs
This project is the official documentation for [Numa](https://github.com/secc/Numa), an open-source AI workspace for churches.

### Local Development
Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally.

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where docs.json is)

```
mintlify dev
```

### Publishing Changes
After making changes to the documentation locally, push them to the default `develop` branch. When a new version of Numa is released, the corresponding release of NumaDocs will be integrated into the `main` branch for production.

#### Troubleshooting
- Mintlify dev isn't running - Run `mintlify install` to re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `docs.json`