# Softadastra Engine

**Offline-first runtime foundations for C++ applications.**

Softadastra Engine helps C++ applications keep working when the network is slow, unstable, expensive, or unavailable.

It provides foundations for local state, write-ahead logging, durable storage, retry, sync, transport, and recovery.

<p align="center">
  <img
    src="https://res.cloudinary.com/dwjbed2xb/image/upload/v1778700690/architecture_ukigg6.png"
    alt="Softadastra Engine architecture"
    width="760"
  />
</p>

## What is Softadastra Engine?

Softadastra Engine is the offline-first runtime layer inside the Softadastra C++ tooling ecosystem.

It is designed for applications that need to:

- save work locally
- persist important operations
- recover after interruption
- retry safely
- synchronize when possible
- keep useful behavior available without depending on a perfect network

## Core model

```txt
write locally
persist safely
recover after failure
retry when needed
sync when possible
```

## Ecosystem role

```txt
Vix.cpp
  -> C++ runtime and developer tooling foundation

Softadastra Engine
  -> offline-first runtime layer

Cnerium
  -> retry-safe backend reliability for Vix applications

Kordex
  -> JavaScript and TypeScript runtime built on Vix.cpp
```

Softadastra Engine is not the whole Softadastra company.

Softadastra Company is focused on C++ tooling.
This repository contains the engine layer.

## Install

Linux and macOS:

```bash
curl -fsSL https://softadastra.com/install.sh | bash
```

Windows PowerShell:

```powershell
irm https://softadastra.com/install.ps1 | iex
```

## Documentation

Read the documentation here:

- https://docs.softadastra.com

## Learn more

- Website: https://softadastra.com
- Documentation: https://docs.softadastra.com
- Repository: https://github.com/softadastra/softadastra
- Vix.cpp: https://vixcpp.com
- Cnerium: https://github.com/softadastra/cnerium
- Kordex: https://github.com/softadastra/kordex

## License

Licensed under the Apache License, Version 2.0. \
See the [LICENSE](LICENSE) file for details.
