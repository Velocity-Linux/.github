<p align="center">
  <img src="branding/banner.png" alt="Velocity OS Banner" style="max-width: 100%; height: auto;">
</p>

# Velocity OS

Velocity OS is a performance-focused Linux distribution engineered for gaming, low latency, and minimal overhead. We prioritize engineering discipline over marketing claims.

## Philosophy

Velocity OS is built on the following principles:

- **Performance first**: Every optimization must be benchmarked. We ship configurations that are measurably better.
- **Low latency**: Reduce scheduling latency, input-to-display latency, and system overhead.
- **Minimal overhead**: Remove unnecessary services, daemons, and abstractions. The system should get out of the way.
- **Fully customizable**: Users have full control. We provide sensible defaults, not walls.
- **Open source**: Every component is auditable. No proprietary binaries or telemetry.
- **Zero telemetry**: We do not collect, transmit, or process any user data.
- **Rolling release**: Users receive continuous updates without periodic reinstalls.
- **Professional engineering**: Code quality, testing, and documentation are not optional.
- **Automation over manual tweaking**: Optimizations belong in the system, not in user configuration files.
- **Stay close to upstream**: We patch and configure upstream software rather than forking aggressively.
- **Maintainability over unnecessary complexity**: Simple, maintainable systems are more reliable.

## Project Goals

- Deliver a Linux distribution that achieves competitive or superior gaming performance compared to mainstream distributions, without gimmicks.
- Maintain a small, focused package repository with rigorous quality controls.
- Provide transparent, reproducible benchmarks for all performance-related changes.
- Build a sustainable community of contributors who value engineering rigor.

## Main Repositories

- **Velocity-Linux/installer**: Custom installer with guided and advanced workflows.
- **Velocity-Linux/packages**: Core package repository and PKGBUILD collection.
- **Velocity-Linux/engine**: System configuration engine, scheduler tunables, and kernel parameter management.
- **Velocity-Linux/kernel**: Kernel patches, custom modules, and low-level configuration.
- **Velocity-Linux/desktop**: Desktop environment customizations, compositor configuration, and shell integration.
- **Velocity-Linux/docs**: Official documentation and user guides.

## Documentation

- **Installation Guide**: https://docs.velocityos.org/install
- **Configuration Reference**: https://docs.velocityos.org/configuration
- **Developer Documentation**: https://docs.velocityos.org/development
- **Benchmarking Guide**: https://docs.velocityos.org/benchmarks

## Contributing

We welcome contributors of all skill levels. See [CONTRIBUTING.md](https://github.com/Velocity-Linux/.github/blob/main/CONTRIBUTING.md) for the development workflow and standards.

Performance-related contributions must include benchmark evidence. See the [Benchmarking Guide](https://docs.velocityos.org/benchmarks) for methodology.

## Development Philosophy

We follow a few simple rules:

- If you cannot measure it, do not claim it improves performance.
- If a change is not tested, it is not merged.
- If a change is not documented, it does not exist.
- If a change is not maintainable, it is technical debt.
- If a change benefits a niche use case at the expense of the default user, it must be optional.

## Community

- **GitHub Discussions**: https://github.com/orgs/Velocity-Linux/discussions
- **Issue Tracker**: https://github.com/orgs/Velocity-Linux/issues
- **Security**: velocityos@tutamail.com

## Current Project Status

Velocity OS is under active development. The current focus is on stabilizing the installer, validating the core package set, and establishing the benchmark suite. Releases are published on a rolling schedule.

Roadmap and status updates are posted in GitHub Discussions and the release notes.
