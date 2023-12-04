
<!-- ![selectTyperQr](https://github.com/puutaro/selectTyper/assets/55217593/98e0aaa1-6a43-4291-bcba-619dd583a5ce)　-->
<!-- ![image](https://github.com/puutaro/selectTyper/assets/55217593/471cb0e7-f976-4aec-971c-953469878b71)　-->
<!-- ![image](https://github.com/puutaro/selectTyper/assets/55217593/49de9932-24ba-475c-8dc7-4d8da58c4f06)　-->
<!-- ![image](https://github.com/puutaro/selectTyper/assets/55217593/6048e08c-3f87-47e2-899a-a51275c92823) -->
![image](https://github.com/puutaro/selectTyper/assets/55217593/2b569930-b46e-4d4e-aaa5-f6e6dd0b4226)

<!-- low  -->
![image](https://github.com/puutaro/selectTyper/assets/55217593/d96dcef7-dda5-43c9-9864-1c67bc886a61)

low image 400  

![selectTyperQr400](https://github.com/puutaro/selectTyper/assets/55217593/dc7e36fd-cf37-4580-b55e-cf55f09fde91)
  

width 300  
 

<img src="https://github.com/puutaro/selectTyper/assets/55217593/dc7e36fd-cf37-4580-b55e-cf55f09fde91" width="300"> 


low image 500  

![selectTyperQr500](https://github.com/puutaro/selectTyper/assets/55217593/1b6d061a-f780-4ddf-951c-103a47a7cea4)

width=300
<img src="https://github.com/puutaro/selectTyper/assets/55217593/1b6d061a-f780-4ddf-951c-103a47a7cea4" width="300">  

lwo iamge
![selectTyperQr](https://github.com/puutaro/selectTyper/assets/55217593/bdaf8ec8-6503-48d9-b93b-f2cc5eb64e27)


<img src="https://github.com/puutaro/selectTyper/assets/55217593/bdaf8ec8-6503-48d9-b93b-f2cc5eb64e27" width="300">  


select typer site  


![image](https://github.com/puutaro/selectTyper/assets/55217593/1bcb080b-2f94-4085-a5c5-40212788a074)
<img src="https://github.com/puutaro/selectTyper/assets/55217593/1bcb080b-2f94-4085-a5c5-40212788a074" width="300">  
　
<img src="https://github.com/puutaro/selectTyper/assets/55217593/d96dcef7-dda5-43c9-9864-1c67bc886a61" width="300">  
<img src="https://github.com/puutaro/selectTyper/assets/55217593/555e8f5f-656a-4faf-bb76-f663c01cfe47" width="300">   

<!-- ![install_qr](https://github.com/puutaro/selectTyper/assets/55217593/555e8f5f-656a-4faf-bb76-f663c01cfe47) -->

# selectTyper.js
----------------

Type by select box for login form, etc.. by puutaro

Table of Contents
-------
<!-- vim-markdown-toc GFM --> 
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


