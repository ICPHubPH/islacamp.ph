# islacamp.ph landing page deployed on icp

## based on icp_simple_site boilerplate

To use this repo, simply override the contents of src folder to the files of your own project.

Run dfx in separate terminal

```
dfx start --clean
```

# Configuring dfx.json

```
{
    "canisters": {
      "icp_simple_site": {
        "frontend": {
          "entrypoint": "src/index.html"
        },
        "source": ["src"],
        "type": "assets"
      }
    },
    "dfx": "0.19.0",
    "version": 1
  }
```

# Deploying your landing page (frontend)

Open VS Code and open a terminal instance and run:

```
dfx deploy
```
