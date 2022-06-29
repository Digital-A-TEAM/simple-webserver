# Simple Web project [![Remove this later](https://img.shields.io/badge/-template-green)](https://digital-ateam.de/)
This is a template for a simple web server Docker setup with Nginx and Php. This is for development purposes only! Here you should insert a brief description of your project.

## Requirements
<details open>
<summary>Windows 10 / Windows 11</summary>

- [WSL](https://docs.microsoft.com/de-de/windows/wsl/install) 
- [Docker Dekstop](https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe?utm_source=github)
- [Git](https://github.com/git-guides/install-git#install-git-on-windows)
- Add any additional information about your project that the developer needs to run the project

</details>

<details>
<summary>macOS High Sierra to Monterey (& M1)</summary>

- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [Git](https://github.com/git-guides/install-git#install-git-on-mac)
- Add any additional information about your project that the developer needs to run the project

</details>

<details>
<summary>Ubuntu</summary>

- [Docker & Docker compose](https://docs.docker.com/engine/install/ubuntu/)
- [Git](https://github.com/git-guides/install-git#install-git-on-linux)
- Add any additional information about your project that the developer needs to run the project

</details>

## Getting started
1. Clone this repository
    ```sh 
    gh repo clone ORG/THIS_REPO
    cd THIS_REPO
    ```
2. Start the docker containers
    ```
    docker-compose up -d
    ```
3. Add a step by step guide

## Helpful command list

_Add helpful commands like this:_

Compile tailwindcss (you can remove the --minify for development)
```sh
npx tailwindcss -o app/dist/tailwind.css  --minify
```
