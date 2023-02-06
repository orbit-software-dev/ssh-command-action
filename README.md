# SSH Workflow

This action runs a specified script on a target system via SSH.

## Inputs

### `Host`

**Required** - The hostname of the system to connect to.

### `User`

**Required** - The user name of the account to connect to the system with.

### `Password`

**Required** - The password of the account to connect to the system with.

## Example Usage

```yaml
uses: orbit-software-development/ssh-command-action@main
with:
  host: host.domain.com
  user: myUsername
  password: myPassword
  script: "echo This Workflow is Awesome!"
```
