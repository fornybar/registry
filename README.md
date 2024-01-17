# Flake registry
Out flake registry

# Register
To register a repo call `repo-to-register` from the `fornybar` organization run:

```bash
nix registry add --registry ./registry.json repo-to-register github:fornybar/repo-to-register
```

# Development

Do all changes on main branch. When you need changes on a nixos version branch, cherry pick required commits from main. For more info see [ADR3](https://github.com/fornybar/arkitektur/blob/main/docs/adr/0003-nix-registry.md).
