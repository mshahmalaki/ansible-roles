# How to use

## Create and activate virtual environment

```sh
python3 -m venv venv
source venv/bin/activate
```

## Upgrade pip package and install requirements packages

```sh
pip3 install -U pip
pip3 install -r requirements.txt
```

## Fetching Collections from git

```sh
ansible-galaxy collection install -r collections/requirements.yml --force --ignore-errors --collections-path collections
```

## Fetching Roles from git

```sh
ansible-galaxy install -r roles/requirements.yml --force --ignore-errors --roles-path roles -g
```
