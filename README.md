DevOps engineer based in Paris. I write mostly Rust, with an interest in systems programming, graphics, and performance.

## Projects

- **[DeadSync](https://github.com/pnn64/deadsync)** - A rhythm-game engine for StepMania/ITG charts, focused on timing, performance, and compatibility.
- **[rssp](https://github.com/pnn64/rssp)** - A Rust library and command-line tool for parsing and analyzing StepMania simfiles.
- **[itgmania-harness](https://github.com/pnn64/itgmania-harness)** = Testing tools that run ITGmania's own code to generate reference results for compatibility checks.

## Upstream contributions

I also contribute performance improvements to existing open-source projects. Some merged examples:

| Project | Contribution |
| --- | --- |
| **wgpu** | [Reduced temporary allocations during bind group creation](https://github.com/gfx-rs/wgpu/pull/10188) |
| **glam** | [Simplified quaternion identity checks](https://github.com/bitshifter/glam-rs/pull/824) |
| **rand** | [Optimized weight lookup and iteration](https://github.com/rust-random/rand/pull/1838) |
| **Rerun** | [Removed allocations when resolving archetype field names](https://github.com/rerun-io/rerun/pull/12921) |
| **image** | [Removed temporary allocations during APNG frame disposal](https://github.com/image-rs/image/pull/3102) |
| **png** | [Removed temporary buffers when writing APNG frame data](https://github.com/image-rs/image-png/pull/714) |
| **zstd-rs** | [Reduced buffer growth and initialization overhead during decoding](https://github.com/gyscos/zstd-rs/pull/374) |
| **rtrb** | [Optimized folding over ring-buffer read chunks](https://github.com/mgeier/rtrb/pull/196) |
| **twox-hash** | [Avoided unnecessary secret copies in seeded XXH3 hashing](https://github.com/shepmaster/twox-hash/pull/127) |

Within the rhythm-game community, I've also contributed [audio sample-rate configuration](https://github.com/itgmania/itgmania/pull/863) and [rendering fixes](https://github.com/itgmania/itgmania/pull/1520) to ITGmania, along with [improvements to the Simply Love theme](https://github.com/Simply-Love/Simply-Love-SM5/pull/789).
