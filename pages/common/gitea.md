# gitea

> Manage Gitea servers.
> More information: <https://docs.gitea.com/administration/command-line>.

- Start the server, use `gitea web` to pass arguments:

`gitea`

- Diagnose setup problems:

`gitea doctor check --all`

- Create a user with username, email, and a random password:

`gitea admin user create --username {{username}} --email {{email}} --random-password`

- Shutdown the running process:

`gitea manager shutdown`

- Backup the instance into a ZIP skipping the database (use a native database dump instead):

`gitea dump --skip-db`

- Dump all docs to `stdout`:

`gitea docs`

- Display help:

`gitea {{[-h|--help]}}`
