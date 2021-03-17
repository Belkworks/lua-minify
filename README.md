
# minify
Forked from [stravant's tool](https://github.com/stravant/LuaMinify)

**NOTE**: The `minify` in this branch does not make variables as small as they can be!

**Importing with [Neon](https://github.com/Belkworks/NEON)**:
```lua
lib = NEON:github('belkworks', 'minify', nil, 'upgrade')
```

Usage:
```lua
lib.minify(code) -- code -> minified code (with obfuscated variables)
lib.beautify(code) -- code -> beautified code
```
