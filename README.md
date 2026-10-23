# Flake registry
Our flake registry

# Register
From the repository root, register a repo called `repo-to-register` from the `fornybar` organization with:

```bash
nix registry add --registry "$PWD/registry.json" repo-to-register github:fornybar/repo-to-register
```

# Development

Do all changes on main branch. When you need changes on a nixos version branch, cherry pick required commits from main. For more info see [ADR3](https://github.com/fornybar/arkitektur/blob/main/docs/adr/0003-nix-registry.md).
