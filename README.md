# PAN

## Getting Started
Clone the repo to a local folder in our machine, for example `~/Documents/code/PAN` (or `Home/Documents/code/PAN`).
```
git clone https://github.com/RuanBispo/PAN.git
```

**Step 1.** Configure your environment using our [docker](docs/docker_config.md) or [conda](docs/conda_config.md) configuration tutorials. Furthermore, we are using the [vscode](docs/vscode_config.md).

**Step 2.** Download the [nuScenes dataset](https://www.nuscenes.org/nuscenes#download) and unzip the following files:
```
nuScenes
|   ├── meta
|   ├── v1.0-trainval
```
script to unzip files:
```bash
bash scripts/unzip_dataset.sh
```
