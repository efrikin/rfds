# RFD(s)

This repository contains RFD(s).

## Prerequisites

- ![d2lang](https://github.com/terrastruct/d2)[^1]

[^1]: d2 binary must be copied to `path/to/project/assert` folder.

## Preview

### Building

```bash
podman kube play quarto-preview.yaml
```

### Recreating

```bash
podman kube play quarto-preview.yaml --replace
```

### Removing

```bash
podman kube play quarto-preview.yaml --down
```

## Debugging

```bash
podman pod logs quarto-preview
```

## References

- [Podman: podman-kube-play](https://docs.podman.io/en/v5.5.1/markdown/podman-kube-play.1.html)
