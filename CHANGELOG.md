# v0.1.6
- [BUG] Fix wrong TCP receiving logic
- Automatically create config directory
- Fix and reword cli help texts

# v0.1.5
- Basic Windows support
- Integrate completion script build in build.rs

# v0.1.4
- Dependency updates

# v0.1.3
- Change table design of `pueue status`

# v0.1.2
- Handle broken UTF8 in `show` with `-f` and `-e` flags.
- Allow restart of `Killed` processes

# v0.1.1

- Replace prettytables-rs with comfy-table
- Replace termion with crossterm
- Add --daemonize flag for daemon to daemonize pueued without using a service manager
- Add daemon-shutdown subcommand for client for killing a manually daemonized pueued.
