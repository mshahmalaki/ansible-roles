## Fetching roles from git

```
ansible-galaxy collection install -r collections/requirements.yml --force --ignore-errors --collections-path collections
```

```
ansible-galaxy install -r roles/requirements.yml --force --ignore-errors --roles-path roles -g
```