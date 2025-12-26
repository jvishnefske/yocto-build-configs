# yocto-build-configs

Declarative Yocto build configurations using KAS. Build embedded Linux images for various hardware targets (Raspberry Pi, i.MX6, x86-64, etc.) with reproducible, containerized builds.

## Quick Start

```bash
git clone https://github.com/jvishnefske/yocto-build-configs.git
cd yocto-build-configs
./scripts/kas-container build genericx86-64.yaml
```

## Available Configurations

- `genericx86-64.yaml` - Generic x86-64 target
- `pi64.yaml` / `pi32.yaml` / `pi0w.yaml` - Raspberry Pi variants
- `imx6.yaml` - NXP i.MX6 boards
- `geode.yaml` - AMD Geode target
- `microblaze.yaml` - Xilinx MicroBlaze soft processor

## Requirements

- Docker (for containerized builds via kas-container)
- Or: Python with `kas` package (`pip install kas`)
