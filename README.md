# OMAGARI
Bevy-Hanabi 3D particle effects editor designed for the next version of https://hexroll.app.

![firework](https://raw.githubusercontent.com/hexroll/omagari/refs/heads/master/images/fireworks.gif)


## Background
This editor was written as an internal tool for the development of hexroll3. Following requests by the Bevy community, it is now open-sourced as-is.

## Getting Started

Clone this repository, and then

```
cd omagari/examples/
cargo run --release 
```

- Omagari uses Hanabi's public API only, utilizing a set of serializable proxy editors that together compose a project file that you can save and load.

- Omagari project files should be named `{project_name}.omagari.ron`.

- Exporting an Omagari project will generate a custom `ron` file built from a set of serialized `EffectAssets` along with some additional metadata.

- Exported files will be named `{project_name}.hanabi.ron`.

- All delete ('`X`') buttons require right-click activation for safety.

## Compatibility

| `Omagari`    | `bevy_hanabi` | `bevy` |
| :--          | :--           | :--    |
| `0.16`       | `0.16`        | `0.16` |

## Contributions

This could could use your care :) so contributions are more than welcome, and showcasing your effects for others to learn from is highly encouraged.

## License

Similar to Hanabi, Omagari is dual-licensed under either:

- MIT License ([`LICENSE-MIT`](./LICENSE-MIT) 
- Apache License, Version 2.0 ([`LICENSE-APACHE2`](./LICENSE-APACHE2)

at your option.

`SPDX-License-Identifier: MIT OR Apache-2.0`
