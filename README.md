# smerge-tools

Custom context menu commands for [Sublime Merge](https://www.sublimemerge.com),
shared across the team.

The repository root is the package root. Clone it into the Sublime Merge
`Packages` directory and the commands show up in the menus. No build step,
no dependencies.

## Commands

Right-click a tag under Locations -> Tags.

| Item             | Tag type    | Output                            |
| ---------------- | ----------- | --------------------------------- |
| View Tag Details | annotated   | message without the PGP signature |
| View Tag Details | lightweight | "no message" notice               |
