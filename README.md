# alaatv

A little script to scrap alaatv.com video urls. Can be used to copy any of scraped links.

## Dependencies

### Build

- [git](https://git-scm.com/downloads) (to clone the repository)
- npm (to install npm dependecies and necessary libraries)

### Runtime

- [nodejs](https://nodejs.org/en/) (to run .js files in cli)
- npm dependencies (installed using `npm install` command in your terminal, cmd or PowerShell when inside `alaatv`s directory)

## Installation

Clone this repository using `git clone https://github.com/nimaaskarian/alaatv.git`, Then `cd alaatv` and use npm to install dependencies using `npm install` command.

## Usage

After installing the dependencies, If you're in the parent directory of `alaatv`, you can run `node alaatv` or `node alaatv [alaatv-url]` or `node .` or `node . [alaatv-url]` if you are in the `alaatv` direcotry to scrape video urls.
You can also use `-d` option to copy first link (it's usually HD_720). If you don't, a prompt will ask you which url you want to copy.
