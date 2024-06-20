# sys-clk-db

Thanks to everyone who contributed to this collection!

**Notes:**  
This format is temporary as we set up a convenient directory structure to be able to directly import community curated profiles!

## Examples

```ini
; The Legend of Zelda: Breath of the Wild
; Overclock CPU when docked
; Overclock MEM to docked clocks when handheld
[01007EF00011E000]
handheld_mem=1600
docked_cpu=1224
```

```ini
; Picross S
; Underclock to save battery with bare minimum settings
[0100BA0003EEA000]
handheld_cpu=612
handheld_mem=665
handheld_gpu=76
```

## Community presets

Those presets comes from our community in the [RetroNX Discord](https://discord.gg/erNC4FB) in the channel `#oc-perf-submissions`.

# Usage
sys-clk is not compatible with the latest HOS and Atmosphere version, here are some forks:
https://github.com/jope82/sys-clk-uncapped-gpu-and-other-extras
https://github.com/hanai3Bi/Switch-OC-Suite