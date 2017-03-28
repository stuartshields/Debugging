# VIP Debugging
This extension is based on the original [Debugging](https://github.com/Chassis/debugging) extension for Chassis. The only difference between this and that extension is that this one doesn't have the Rewrite Rules Inspector installed since the mu-plugins folder already had it installed.

A [Chassis](https://github.com/Chassis/Chassis) extension to install and activate common WordPress plugins used for debugging during development.

## What's this plugin do

This Chassis extension installs and activates the following plugins:

1. [Debug Bar](https://wordpress.org/plugins/debug-bar/)
2. [Debug Bar Extender](https://wordpress.org/plugins/debug-bar-extender/)
3. [Debug Bar Cron](https://wordpress.org/plugins/debug-bar-cron/)
4. [Debug Bar Transients](https://wordpress.org/plugins/debug-bar-transients/)
5. [Log Deprecated Notices](https://wordpress.org/plugins/log-deprecated-notices/)

## Usage
1. Follow the VIP Classic setup directions
2. Add this extension to your extensions directory `cd debugging && git clone git@github.com:stuartshields/vip-debugging.git extensions/vip-debugging`
3. `vagrant provision` to install the plugins
