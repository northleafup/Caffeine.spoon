## What is this

It is a spoon for hammerspoon



## Where is from 

Copy and change from [Here](https://github.com/Hammerspoon/Spoons/tree/master/Spoons)



## How to use in MacOs  

###### First 

```bash
cd ~
cd .hammerspoon/Spoons
git clone https://github.com/northleafup/Caffeine.spoon.git
```

###### Second

Create yourseft config .If there is no directory "~/.hammerspoon/private", please make it 

```bash
cd ~
cd .hammerspoon
mkdir private
```

###### Three

If you want to update the `active` and `inactive` image, you can redefine it . 

Copy example config:

```bash
cd ~
cp .hammerspoon/Spoons/Caffeine.spoon/caffeine.lua .hammerspoon/private/caffeine.lua
```

Then update the `activeIcon`  or `inactiveIcon` value 

```lua
activeIcon = "caffeine-on.pdf"
inActiveIcon = "caffeine-off.pdf"
```

Next you shoud place the image file to folder `~/.hammerspoon/Spoons/Caffeine.spoon/`

###### Four

If you use [my config](https://github.com/northleafup/my-hammerspoon), please refer [this](https://github.com/northleafup/my-hammerspoon#2-load-specify-spoon).

else：

Update init.lua file ,add content as follow

```lua
hs.loadSpoon("Caffeine")
```



## Thanks To

[dot_hammerspoon](https://github.com/scottcs/dot_hammerspoon)