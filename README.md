# YaManet
**Yet another Manet**

# What is Manet?
- An awesome app
- https://github.com/vbauer/manet

# Installation

## git clone and yarn install (npm install)
```bash
$ git clone git@github.com:corselia/yamanet.git
$ cd amanet
$ yarn install
```

## Edit a configuration file
- Please refer an official document
    - https://github.com/vbauer/manet/blob/master/README.md

```bash
$ vim ./to_copy_files/config/default.yaml
```

## Copy a configuration file and web front files
- If you change web front files, edit [to_copy_files/public/*](/to_copy_files/public)

```bash
$ cp ./to_copy_files/config/default.yaml ./node_modules/manet/src/config
$ cp -r ./to_copy_files/public ./node_modules/manet
```

# Boot YaManet
```bash
$ ./start_yamanet.sh
```

# Stop YaManet
```bash
$ pkill -f manet
```

# Note
If you use OS X, perhaps it doesn't work correctly. Please refer a following issue.
- https://github.com/nwjs-community/nw-builder/issues/75

# LICENSE
- [MIT LICENSE](/LICENSE)
