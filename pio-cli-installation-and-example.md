# Installation

1. To install or upgrade PlatformIO Core paste the following command at a Terminal prompt:

    ```bash
      python3 -c "$(curl -fsSL https://raw.githubusercontent.com/platformio/platformio/master/scripts/get-platformio.py)"
    ```

2. Export PlatformIO executables’ directory to the PATH environmental variable

    ```shell
      #Export PlatformIO executables’ directory to the PATH environmental variable
      export PATH=$PATH:/home/pi/.platformio/penv/bin
    ```

For complete details on how install PlatformIO Core (CLI) see [this offical documentaiton](https://docs.platformio.org/en/latest/core/installation.html#super-quick-mac-linux).

# Build an environment and upload it to a target

```bash
pio run -e heltecv2demo -t upload
```

For more details on the above command see [Example 4](https://docs.platformio.org/en/latest/core/userguide/cmd_run.html#examples).


See the [this documentation page of the PIO CLI Guide](https://docs.platformio.org/en/latest/core/userguide/cmd_run.html) for examples on how to use `pio run`.
