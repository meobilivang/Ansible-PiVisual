# :dart: `Ansible PiDash`

```text
 _______________________________________
/ Quickly boostrap environment & launch \
\ PiVisual on local Rasberry Pi         /
 ---------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

## :books: How to run Playbook?

## :wrench: Set up

- Install `Ansible`

    - With `pip`:
    ```bash
    $ python3 -m pip install ansible
    ```

    - With `dnf` (On `RHEL`-like systems):

    ```bash
    $ sudo dnf install ansible
    ```

- Install required modules
```bash
$ ansible-galaxy install -r requirements.yml
```

## :gear: Playbook

- Run Ansible playbook
    - Add `-v` for verbose outputs
```bash
$ ansible-playbook main.yml -K
```
