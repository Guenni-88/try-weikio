# Weik.io Integration Development Container

[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/weikio/try-weikio)

Weik.io Integration Development container is for Architects and Developers building integrations using the Weik.io Integration Platform.

This **development container** is a running container with a well-defined Weik.io tool/runtime stack and its prerequisites. You can try out development containers with **[GitHub Codespaces](https://github.com/features/codespaces)** or **[Visual Studio Code Dev Containers](https://aka.ms/vscode-remote/containers)**.

## Note

VS Code sometimes likes to cache the Development Container files. If you have issues running the devcontainer directly from VS Code, you can try cloning this repository and then opening it through VS Code as a Devcontainer.

Alternatively make sure to delete the devcontainer volumes to start fresh.

## Login details

Here are the login details for Weik.io instance running in the Devcontainer:

* Username: dev@weik.io
* Password: password
* ApiKey: api.key

The Weik.io CLI is configured with the local environment.

## Setting up the development container

### GitHub Codespaces
Follow these steps to open this sample in a Codespace:
1. Click the **Code** drop-down menu.
2. Click on the **Codespaces** tab.
3. Click **Create codespace on main** .

For more info, check out the [GitHub documentation](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces/creating-a-codespace#creating-a-codespace).

### VS Code Dev Containers

If you already have VS Code and Docker installed, you can click the badge above or [here](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/microsoft/vscode-remote-try-go) to get started. Clicking these links will cause VS Code to automatically install the Dev Containers extension if needed, clone the source code into a container volume, and spin up a dev container for use.

Follow these steps to open this sample in a container using the VS Code Dev Containers extension:

1. If this is your first time using a development container, please ensure your system meets the pre-reqs (i.e. have Docker installed) in the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started).

2. To use this repository, you can open a locally cloned copy of the code:

   - Clone this repository to your local filesystem.
   - Press <kbd>F1</kbd> and select the **Dev Containers: Open Folder in Container...** command.
   - Select the cloned copy of this folder, wait for the container to start, and try things out!
   
## Things to try

Once you have this sample opened, you'll be able to work with it like you would locally.

Some things to try:

1. Create new integration
2. Develop and test the new integration
3. Publish the integration to Weik.io
4. Run the integration
5. View the integration in Weik.io UI

## License

Licensed under the MIT License. See LICENSE in the project root for license information.
