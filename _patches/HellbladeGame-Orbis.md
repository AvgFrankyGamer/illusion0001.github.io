# Hellblade: Senua's Sacrifice

## Resolution Patch

[Framerate analysis](https://youtu.be/DO8zPsX_ahE)

This game already runs with uncapped framerate.

Only useful for Base Console.

In file `eboot.bin`

<details>
<summary>Code 1.02 (Click to Expand)</summary>

```
# all code below must be applied

# allow screenpercentage to be used
8B 05 77 87 20 03 83 38 01 75 0D

8B 05 77 87 20 03 83 38 01 74 0D

# call
48 8B 05 4C 7D 03 03

67 67 E8 7D 0A 22 00

# main code
E8 0C E1 49 01 90 90 90 90 90 90 90 90 90 90 90 90 55 48 89 E5 41 57 41 56 41 54 53 48 89 D3 45 89

E8 0C E1 49 01 90 90 90 90 90 90 90 90 90 90 90 90 C3 48 8B 05 C8 72 E1 02 C7 00 00 00 86 42 C3 89

# Presets:

# 540p target
C7 00 00 00 48 42 C3 89

# 720p target
C7 00 00 00 86 42 C3 89

# 900p target
C7 00 F6 A8 A6 42 C3 89

# 67.0f  = 00 00 86 42
# 83.33f = F6 A8 A6 42
```

</details>