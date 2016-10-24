# GPIO

A small utility script for easily exporting, unexporting and read, writing GPIO pins on RaspberryPi or other development boards.

### How To

```
Usage: gpio [export|direction|read|write|unexport]

       Param1    | Param2 | Param3
       ---------------------------
       export    | PIN    |
       unexport  | PIN    |
       direction | IN/OUT | PIN
       read      | PIN    |
       write     | VALUE  | PIN
```

### Example

```bash
gpio e 72       # exports pin 72
gpio d o 72     # sets direction to out
gpio d i 72     # sets direction to in
gpio r 72       # reads from pin 72
gpio w 1 72     # writes 1 to pin 72
gpio u 72       # unexports pin 72
```
