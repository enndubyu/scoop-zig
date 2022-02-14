# scoop-zig

A scoop bucket for the zig compiler and related tools. Feel free to create an issue requesting any useful zig tools that are missing from the bucket.

To install zig:

```sh
# add scoop bucket
scoop bucket add scoop-zig https://github.com/enndubyu/scoop-zig

# install zig
scoop install zig
```

## Tools in this bucket:
- **zig** - *zig compiler* 
- **zig-dev**[^1] - *zig compiler (development version)*
- **zls** - *language server for zig*

[^1]: zig-dev is aliased as both *zig* and *zig-dev* unless zig stable is also installed (in which case *zig* will execute zig stable)
