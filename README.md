# MacBook
Provisioning tool for OSX

## Usage

Run init script

```
curl https://raw.githubusercontent.com/makky3939/MacBook/master/init.sh | sh
```

Clone this repository

```
mkdir ~/Projects
```

Execute the notebook

```
HOMEBREW_CASK_OPTS="--appdir=/Applications" ansible-playbook -i hosts -v localhost.yml -K
```
