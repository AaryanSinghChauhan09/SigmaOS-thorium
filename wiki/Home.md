# SigmaOS-thorium

SigmaOS integration component for **Thorium browser**.

## Commands

```bash
sigmaos-thorium install   # install package + deploy defaults
sigmaos-thorium deploy    # copy config templates to $HOME
sigmaos-thorium status    # binary/package/config report
sigmaos-thorium reset     # remove deployed config
sigmaos-thorium open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
