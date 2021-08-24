# gen-dockerfile-install

auto generate npm install script for each dependency in Dockerfile for caching

[![npm Package Version](https://img.shields.io/npm/v/@beenotung/tslib.svg?maxAge=3600)](https://www.npmjs.com/package/@beenotung/tslib)

## Usage Example
```shell
# init the Dockerfile
> gen-dockerfile-install --init

# update Dockerfile according to the dependency list in package.json
> gen-dockerfile-install
```

## License

This project is licensed with [BSD-2-Clause](./LICENSE)

This is free, libre, and open-source software. It comes down to four essential freedoms [[ref]](https://seirdy.one/2021/01/27/whatsapp-and-the-domestication-of-users.html#fnref:2):

- The freedom to run the program as you wish, for any purpose
- The freedom to study how the program works, and change it so it does your computing as you wish
- The freedom to redistribute copies so you can help others
- The freedom to distribute copies of your modified versions to others