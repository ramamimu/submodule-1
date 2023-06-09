## How to add submodule

`git submodule add <link_clone_github>`

## How to Clone with Submodule

`git clone --recurse-submodules <link_clone_github>`

## How to First Update

`git submodule update --init --recursive`

## How to update submodule to last commit

`git submodule update --remote`

## How to pull submodule

`git pull --recurse-submodules` or `git submodule update`

## How to Pull all modules from super-repo

`git submodule foreach "git pull"`
