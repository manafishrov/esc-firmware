# Manafish ESC Firmware

Manafish's fork of [AM32](https://github.com/am32-firmware/AM32) for the ROV's
brushless-motor ESCs. It carries motor-control and safety changes specific to
the vehicle, and imports upstream fixes selectively.

## Build

```sh
make arm_sdk_install
make product
```

`make targets` lists every board target. Builds are written to `obj/`.

## License

[GPL-3.0](LICENSE). The original AM32 project and its contributors retain their
copyrights.
