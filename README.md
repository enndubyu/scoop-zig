# :zap: scoop-zig :zap:

[![Build status](https://ci.appveyor.com/api/projects/status/7tl21hvdnb3ysl36?svg=true)](https://ci.appveyor.com/project/enndubyu/scoop-zig)

A scoop bucket for the zig compiler and related tools. Updated bihourly. Feel free to create an issue requesting any useful zig tools that are missing from the bucket.

To install zig:

```sh
# add scoop bucket
scoop bucket add scoop-zig https://github.com/enndubyu/scoop-zig

# install zig
scoop install zig
```

## Tools in the bucket:

- **zig** - *[zig](https://ziglang.org/) compiler*
- **zig-dev**[^1] - *zig compiler (development version)*
- **zig-mach**[^2] - *zig compiler ([mach](https://machengine.org/) project's latest [nominated](https://machengine.org/about/nominated-zig/) zig version)*
- **zls** - *language server for zig*

[^1]: `zig-dev` is aliased as both `zig` and `zig-dev` unless zig stable is also installed (in which case `zig` will execute zig stable)
[^2]: `zig-mach` is aliased as both `zig` and `zig-mach` unless zig stable is also installed (in which case `zig` will execute zig stable)
