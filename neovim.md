
# WSL & Windows Terminal & Ubuntu
The first thing to get going.  Many docs on the internet for this, however, the windows store is now the go to place to get all 3 of these.

# Docker
The aim is to be able to run dev from a container, for a quickly reproduceble dev environment, the host machine is then just a console.

Install Steps
 - TODO

# Neovim
Why vim?  Seems to be more current that VIM with essentially the same development experience.  But has the edge at certain pain points (plugins), certainly when starting out for the first time.

Install Steps
 - `sudo apt-get install neovim` 

##  Neovim Plugins
The heart of the dev experience.

Started with VIM first but had some problems getting vim-go running and read around on the internet that neovim was a more out of the box experience.  So got cracking with the following excellent medium post:

https://medium.com/@yanglyu5201/neovim-setup-for-golang-programming-68ebf59336d9

As well as getting setup for GO development, this also forms part of the basic neovim experience as well, and provides basic plugin support for :
 - Theme (GruvBox)
 - Git
 - Nerdtree
 - Basic config setup

have added
 - vim-airline
 - vim-airline-themes

### notes
  - window navigation is bound to `<ctrl>-h/j/k/l`, no need for an opening `<ctrl>-w` first.  Althrough `<ctrl-w>` works, and is still good for resizing all.  e.g. `<ctrl>-w =`
  - NerdTree is setup to open and take focus.  
    - Go the folder you want and enter `gs` per file to open multiple documents into their own windows.
    - `s` will open a file into a new split window and put the focus into the new window

### Go

#### Install Go
Following the instructions on : https://go.dev/doc/install

#### Neovim plugins
 - vim-go

### Javascript / Typescript


### .net







