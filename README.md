# chuột phải powershell -> run admin và gõ lệnh
Set-ExecutionPolicy RemoteSigned -scope CurrentUser

Y

iwr -useb get.scoop.sh -outfile 'install.ps1'

.\install.ps1 -RunAsAdmin

scoop install gow git-with-openssh

scoop bucket add extras https://github.com/thvlt/Extras.git

scoop install d8 scratch Flowgorithm thonny TyperShark
