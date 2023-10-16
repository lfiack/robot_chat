# robot_chat
My (as a prof) take at building a cat/mouse robot

## Make the project work
This project uses a submodule for the KiCAD library. To get it properly, use the `--recursive` option when cloning the repo :

```bash
git clone --recursive git@github.com:lfiack/robot_chat.git
```

If you forgot the `--recursive` option (as I do quite often), you can type the following command :

```bash
git submodule update --init --recursive
```
