# Build with Docker

```sh
$ git clone https://github.com/qmk/qmk_firmware.git
$ cd qmk_firmware/
$ docker run -e keymap=c4software -e keyboard=xd75 --rm -v $('pwd'):/qmk:rw edasque/qmk_firmware
```

![Layout](./keyboard-layout.png)