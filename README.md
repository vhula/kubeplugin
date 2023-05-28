# kubeplugin

## Installation

```bash
curl -LO https://raw.githubusercontent.com/vhula/kubeplugin/main/scripts/kubeplugin
chmod +x ./kubeplugin
sudo mv ./kubeplugin /usr/local/bin/kubectl-kubeplugin
```

![Installation Demo](.res/kubeplugin-install-demo.gif)

## Usage

```bash
kubectl kubeplugin node <namespace>
kubectl kubeplugin pod <namespace>
kubectl kubeplugin --help
```

