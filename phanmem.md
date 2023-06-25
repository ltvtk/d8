Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
iex "& {$(irm get.scoop.sh)} -RunAsAdmin"
scoop install git-with-openssh
scoop bucket add ltvapps https://github.com/thvlt/ltvapps
scoop install TyperShark logo32
scoop bucket add extras
scoop install thonny