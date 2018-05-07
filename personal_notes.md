# Personal Notes

## Linux on Windows

### Bash on Ubuntu on Windows

It turns out that bash on Ubuntu on Windows is actually quite old (14.04 LTS at the time of writing) so it's better to opt-in for the Ubuntu App available on the Microsoft Store.

## Windows Updates

### Registry to trigger Microsoft or other source

Open RegEdit, go to:

`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsUpdate\AU`

..and change the key `UseWUServer` from 1 to 0.

After that, reboot the computer. Then you should be able to enable `Developer Mode`.

Please change the key back to 1 after doing the installation. 
