# Bootstrap Scripts

This repository provides installation scripts for setting up Docker and NVIDIA drivers on Ubuntu systems.

## Usage

You can run the installation scripts with a single command using `curl` and `bash`.

### Install Docker and Docker Compose

```sh
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/fshilver/bootstrap/main/docker/ubuntu/install.sh)"
```

### Install NVIDIA Drivers and Container Toolkit

```sh
sudo bash -c "$(curl -fsSL https://raw.githubusercontent.com/fshilver/bootstrap/main/nvidia/ubuntu/install.sh)"
```

## Disclaimer

These scripts are intended for Ubuntu systems. Please review the scripts before running them on your machine.
