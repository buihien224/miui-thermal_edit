# miui-thermal_edit
Remake miui-thermal editor base on https://github.com/helloklf/vtools/tree/master/mi-thermal-config

**Requirement**
1. Make sure you have Debian base ditros
2. Make sure you have android 12 device (Rooted if you want install module)
3. Make sure you has setup before Run

**Setup**
>      sudo apt-get install -y zip unzip android-tools-adb android-tools-fastboot

**Decode**

`Put thermal*.conf under "input" folder`
>      ./thermal d

**Encode**
`Must run Decode at first`
>      ./thermal e

**Encode and Install Magisk Module**
`Remember give Root permission in your phone`
>      ./thermal e i
