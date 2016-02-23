# Ledgerd Wallet
从ripple-client-desktop-1.4.0复制，并对修复了一些bug，使其能够在windows上打包发布。

##开发环境
- Windows 10
- nodejs 4.2.6
- python 2.7.11
- Visual Studio 2015
- WebStorm 10.0.4

## Install Dependencies

- Fork and clone the ledgerd-wallet repository
- Run `npm install`(由于使用的一些库版本太老，如果遇到问题多次运行此命令)
- Run `npm install -g gulp@3.9.0`

## Build

- In the cinapay-client-desktop repository, make a copy of the `config_example.js` file and name it `config.js`
- Run `gulp` in your command line for development

- Run `gulp packages` in your command line for the production ready client
- Your desktop client is in the `packages/Ledgerd-x.x.x` directory
