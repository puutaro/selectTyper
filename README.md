  
<div><img src="https://github.com/puutaro/selectTyper/assets/55217593/dc7e36fd-cf37-4580-b55e-cf55f09fde91" width="300">  </div>
  
<div><img src="https://github.com/puutaro/selectTyper/assets/55217593/555e8f5f-656a-4faf-bb76-f663c01cfe47" width="300"></div> 


# selectTyper.js
----------------

Type by select box for login form, etc.. by puutaro

Table of Contents
-------
<!-- vim-markdown-toc GFM --> 
* [Installation](#installation)
* [Usage](#usage)
* [Cmd Variables](#cmd-variables)
	* [Keyboard](#keyboard)
	* [valueList](#valuelist)
		* [How to register value](#how-to-register-value)
		* [How to type by this select box](#how-to-type-by-this-select-box)
		* [Modifier kind table](#modifier-kind-table)
* [Setting variables](#setting-variables)
	* [terminalFontZoom](#terminalfontzoom)
	* [scriptFileName](#scriptfilename)


## Installation
------------------------

1. Install [ComamndClick](https://github.com/puutaro/CommandClick#app-installation) to your android
2. Install this fannel by [install repo](https://github.com/puutaro/CommandClick/blob/master/USAGE.md#install-fannel) or QR code


## Screenshots
--------

<a href="https://github.com/puutaro/selectTyper/assets/55217593/af57e47d-6220-4adf-a767-55d3a45eb992"><img src="https://github.com/puutaro/selectTyper/assets/55217593/af57e47d-6220-4adf-a767-55d3a45eb992" width="45%" /></a>
<a href="https://github.com/puutaro/selectTyper/assets/55217593/b2e5264c-3353-42c6-8c3f-015155508a7e"><img src="https://github.com/puutaro/selectTyper/assets/55217593/b2e5264c-3353-42c6-8c3f-015155508a7e" width="45%" /></a>

## Usage
--------

This [fannel](https://github.com/puutaro/CommandClick/blob/master/md/developer/glossary.md#fannel) is triggered after you visit form web page: `google auth`, `github auth`, etc..

1. Visit form web page 
2. (System register page url)
3. This [fannel](https://github.com/puutaro/CommandClick/blob/master/md/developer/glossary.md#fannel) trigger in history or index

## Cmd Variables
--------

This [fannel](https://github.com/puutaro/CommandClick/blob/master/md/developer/glossary.md#fannel) save your input for login form, etc..


### Keyboard

| key name | description |
| --------- | --------- |
| `NEXT` | Move next tab index |
| `BACK` | Move previous tab index |
| `ENTER` | enter key |
| `Input` | prompt by suggest |



### valueList 

Retrieve pre-registerd value.

#### How to register value

1. Type one linear value you wont to register.
2. Press "RG" button 

#### How to type by this select box

1. Tap dropdown.
2. Select one from value list.

- pre reserved value

| name | description |
| --------- | --------- |
| `-` | Escape that you type by select box |
| `DELETE` | Delete current input text contents |
| `NEXT` | Move next tab index |

- If you wont to edit keys file, this is bellow.

[selectTyperDir](https://github.com/puutaro/CommandClick/blob/master/md/developer/directory_structure.md#fannel_dir)/selectTyperDir/list/selectValueList.txt


#### Modifier kind table

Enable to register modifier key conbination

| Modifier | example |
| ----------- | ----------- |
| `ctrl+shift+alt` | `ctrl`\+`shift`\+`alt`\+r -> ctrl\_shift\_alt\_\_\_r |
| `ctrl+shift` | `ctrl`\+`shift`\+v -> ctrl\_shift\_\_\_v |
| `ctrl+alt` | `ctrl`\+`alt`\+c -> ctrl\_alt\_\_\_c |
| `ctrl` | `ctrl`\+z -> ctrl\_\_\_z |
| `shift` | `shift`\+a -> shift\_\_\_a |
| `alt` | `alt`\+b -> alt\_\_\_b|

- Modifier key conbination concat by `___`.

## Setting variables
---------

### terminalFontZoom 
Adjust terminal font size (percentage)

### scriptFileName 
Rename script name


