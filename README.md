# Boosted ReVOLT! Dashboard

More information about the Boosted ReVOLT! Dashboard on [michael-castiau.blogspot.com](https://michael-castiau.blogspot.com/2021/05/boosted-rev-custom-dashboard-vesc.html)

This repository contains the executable binairies of the Boosted ReVOLT! Dashboard in `.bin` format.

The binairies can be found in the [releases](https://github.com/MichaelCastiau/boosted-revolt-dashboard/releases) of this repository.

## Flashing Your Dashboard

The dashboard includes a Tag-Connect 6-pin ARM headless connector.
To update your dashboard manually, please refer to the STLink (V2/V3) SWD debugger solutions of Tag-Connect.

You'll need a:
- Tag-Connect cable with a 6-pin ARM Connector (available on tag-connect.com)
- STLink V2/V3/V3 Mini programmer (available on Amazon or other distributors)

There are two viable solutions:

### [SWD Solution ARM20-CTX](https://www.tag-connect.com/debugger-cable-selection-installation-instructions/st-link-v2) (STLink V2)

> See "SWD Solution using ARM20-CTX"

![arm](./ARM20.png)

For the STLink V2 programmer information, visit official page [on ST Microelectronics website](https://www.st.com/en/development-tools/st-link-v2.html).

### [SWD STDC14 Connector](https://www.tag-connect.com/debugger-cable-selection-installation-instructions/stlink-v3mini) (STLink V3, STLink V3 Mini)

> See "SWD using the Cortex STDC14 connector with 6 Pin connector on target board"

![cortex](./ST-14.png)

For the STLink V3 Mini programmer information, visit official page [on ST Microelectronics website](https://www.st.com/en/development-tools/stlink-v3mini.html).

Both solutions are compatible with the STM32L4 microcontroller present on the board. However, the V3 version of the STLink features ST's most recent product updates.

To flash the firmware, please use the official [ST Program Tool](https://www.st.com/en/development-tools/stm32cubeprog.html)
