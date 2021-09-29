# Home Assistant Add-on: CouchPotato

CouchPotato (CP) is an automatic NZB and torrent downloader. You can keep a "movies I want"-list and it will search for NZBs/torrents of these movies every X hours. Once a movie is found, it will send it to SABnzbd or download the torrent to a specified directory.

![Supports amd64 Architecture][amd64-shield] ![Supports aarch64 Architecture][aarch64-shield] ![Supports armhf Architecture][armhf-shield]

## About

This add-on allows you to run CouchPotato within Home Assistant.

## Installation

Follow these steps to get the add-on installed on your system:

1. Navigate in your Home Assistant frontend to Supervisor -> Add-on Store.
2. Find the "CouchPotato" add-on and click it.
3. Click on the "INSTALL" button.

## How to use

Start the add-on if it is not already running and access it via the panel to configure the application. The `share`, `ssl`, and `backup` directories are mounted for your convenience.

## Configuration

Via the application's settings page.

## Support

While there is no warranty or support, you are welcome to raise an [Issue](https://github.com/nkm8/hassio-addons/issues).
