# go-template

Template for general Go development. General applications are designed to execute until completion.

**Docker** is utilized to eliminate any uniqueness in developer environments.

## Development Workflow

1. Make changes to the source code.

2. Test changes by building and executing the Docker container **locally**.

```sh
# Build
./scripts/build.sh

# Execute
./scripts/run.sh
```