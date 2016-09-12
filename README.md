# RDP
How to install RDP on server

Create a scheduler
Create two files
----------------------------------------------------------
# Reset120.cmd
regedit /s C:\Windows\Reset120.reg
----------------------------------------------------------
# Reset120.reg

Windows Registry Editor Version 5.00

[HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Terminal Server\RCM\GracePeriod]
"L$RTMTIMEBOMB_1320153D-8DA3-4e8e-B27B-0D888223A588"=-
----------------------------------------------------------
