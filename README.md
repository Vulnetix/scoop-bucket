# Vulnetix Scoop Bucket

[Scoop](https://scoop.sh/) bucket for [Vulnetix CLI](https://github.com/Vulnetix/cli) on Windows.

## Installation

```powershell
# Add the bucket
scoop bucket add vulnetix https://github.com/Vulnetix/scoop-bucket

# Install the CLI
scoop install vulnetix

# Verify installation
vulnetix --version
```

## Upgrade

```powershell
scoop update vulnetix
```

## Uninstall

```powershell
scoop uninstall vulnetix

# Optionally remove the bucket
scoop bucket rm vulnetix
```

## Available Packages

| Package | Description |
|---------|-------------|
| `vulnetix` | Vulnetix CLI for vulnerability management |

## Links

- [Vulnetix CLI Documentation](https://docs.cli.vulnetix.com/)
- [GitHub Releases](https://github.com/Vulnetix/cli/releases)
