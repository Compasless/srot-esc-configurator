# SROT ESC Configurator

This is the standalone Compasless configurator repository. Firmware source belongs
in srot-esc-firmware; hardware-flasher, control-board and ground-station source remain separate.

Read README.md, docs/BRAND.md and upstream.lock.json. Keep 3D fixed and normalize
MOTOR_DIRECTION to 3 on every parameter write. Preserve SHA-256, layout, MCU, CRC,
bootloader and readback checks. Never expose force/ignore-layout controls or motor tests.
Tests must use simulated ports, never real serial hardware.

Deploy successful builds through GitHub Pages. Run npm run build, npm test and
npm run qa after functional changes. Preserve AGPL notices and source availability.
Use the supplied company mark without distortion; respect the exact COMPASLESS spelling.
