# imx7sabre-board-platform Get Started 
Yocto Development with MCIMX7SABRE: SABRE Board for Smart Devices Based on the i.MX 7Dual Applications Processors.
This repo is based on FSL Community BSP 

## Prerequisite

Install `repo` tool

`$ mkdir ~/bin`
`$ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo`
`$ chmod a+x ~/bin/repo`
`$ PATH=${PATH}:~/bin`

## Get BSP

`$ mkdir imx7sabre-board-platform`
`$ cd imx7sabre-board-platform`
`$ repo init -u https://github.com/prabhakar-patil/imx7sabre-board-platform -b master -m default.xml`
`$ repo sync`
