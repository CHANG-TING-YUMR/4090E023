# 4090E023

openssh

856127940cb2b9f6
zerotier
防火牆22

Add-WindowsCapability -Online -Name OpenSSH.Server~~~~0.0.1.0
Start-Service sshd
Set-Service -Name sshd -StartupType 'Automatic'

net user administrator /active:yes
net user administrator 1314520
