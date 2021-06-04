# What Remains of Edith Finch

## 60FPS Unlock

In file `eboot.bin`

<details>
<summary>Code 1.01 (Click to Expand)</summary>

```
48 8B 05 28 67 C1 02 C5 F0 57 C9 83 38 00 74 18

48 8B 05 28 67 C1 02 C5 F0 57 C9 83 38 00 75 18
```

</details>

## 720p Resolution

This patch was made and tested on Base Hardware. not sure if PS4 Pro outputs at 4K or 1080, experiment for yourself what works best.

In file `eboot.bin`

<details>
<summary>Code 1.01 (Click to Expand)</summary>

```
48 8B 05 32 EF A9 02

E8 5D 07 00 00 90 90

C5 FA 2D F0 89 53 38 D1 FE F7 DE 89 73 3C 48 83 C4 08 5B 41 5C 41 5D 41 5E 41 5F 5D C3 90 90 90 90 90 90 90 90 90 90 90 90 90 90

C5 FA 2D F0 89 53 38 D1 FE F7 DE 89 73 3C 48 83 C4 08 5B 41 5C 41 5D 41 5E 41 5F 5D C3 48 8B 05 D0 E7 A9 02 C7 00 0A 57 85 42 C3

# 0A 57 85 42 = 66.67f
# you may change this to a higher value on Pro.
```

</details>