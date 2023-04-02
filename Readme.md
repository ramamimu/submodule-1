## How to Clone with Sub-module

`git clone --recurse-submodules https://github.com/chaconinc/MainProject`

## How to Update Sub-module

`git submodule update --remote DbConnector`

## How to Pull Sub-module

`git pull --recurse-submodules` or `git submodule update`

## How to Pull from Super-repo

`git submodule foreach "git pull"`