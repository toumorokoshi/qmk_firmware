# Toumorokoshi's HotDox76v2 Firmware

@toumorokoshi's firmware for the HotDox76v2.

I'm using this configuration vs the stock
firmware as the stock had a few issues:

- mouse keys were not enabled.
- using mod tap layouts triggered the hold variant constantly.

Since I'm primarily using this for the configuration, I'm using stock keybindings and configuring with via.

This keymap also does the following:

- Forces NKRO on
- Enables:
    - VIA
    - Mouse Key
    - Extra Key
    - RGB Matrix
- Disables:
    - The Command Feature
    - The Swap Hands feature

## Flashing Instructions

run:

```
make hotdox76v2:toumorokoshi
make hotdox76v2:toumorokoshi:flash
```

And flash both sides separately. With this firmware only plugging the device into the
left hand side works.