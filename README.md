# ansible-playbooks.
My Ansible playbooks:
- `update.yml` updates the system (naturally);
- `bootstrap.yml` configures Tailscale.

## Dependencies

### `community.general` collection

See the [Ansible docs](https://docs.ansible.com/ansible/latest/collections_guide/collections_installing.html) on how to install collections.

At the time of writing, this should work:
```bash
$ ansible-galaxy collection install community.general
```

### `artis3n.tailscale`

Used to manage Tailscale.

To install:
```bash
$ ansible-galaxy install artis3n.tailscale
```


##