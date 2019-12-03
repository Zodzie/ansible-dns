ubuntu dns server with ansible

- first step run playbook with extra variable `action = install`
- then run playbook with extra variable `action = configure`
- optionally update only with `action = update`
- optionally configure one dns server (e.g. dns secondary) with `action = configure-secondary`