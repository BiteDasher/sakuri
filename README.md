# sakuri

Self-written bash script for AUR. Just to do something by myself.

## Dependencies:
jq: parse json \
git: clone from AUR \
curl: git dependency \
bash: of course \
sed: parse information

## How-to use:

  **sakuri i (names of aur packages) for install package(s).\
	sakuri ia (names of aur packages) for installing package(s) from cache.\
  sakuri r (names of aur packages) for remove package(s).\
  sakuri ch (names of aur packages) for check package(s) for updates.\
	sakuri cha for check all packages for updates.\
  sakuri c for cleaning all sakuri data.\
	sakuri cc for cleaning all sakuri packages cache data.\
  sakuri l for watch a manually (AUR) installed packages.\
  sakuri w for this welcome message.\
	sakuri s (name of aur package) for search.\
	sakuri g (names of aur packages) for ignore package(s) for checking updates.\
	sakuri ug (names of aur packages) for removing package(s) from ignore list.\
	sakuri gl for watch on ignored packages.\
	sakuri u for updating all AUR packages.**
	
# Exit codes:
1 - Standard error. User forgot to write what he wants to do. \
2 - Input error. User answered incorrectly or did not answer at all. \
3 - Internet error/package doesn't exists. User does not have internet access or package does not exist on AUR. \
4 - Makepkg error. Error in makepkg command.

## AUR git clone link:

https://aur.archlinux.org/sakuri.git
