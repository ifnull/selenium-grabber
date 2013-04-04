## Installation ##
```shell
brew install selenium-server-standalone  
ln -sfv /usr/local/opt/selenium-server-standalone/*.plist ~/Library/LaunchAgents
launchctl load ~/Library/LaunchAgents/homebrew.mxcl.selenium-server-standalone.plist
pip install selenium  
```
## Usage ##
```shell
python go.py <path_to_sitemap> <base_path> <image_output_path>
```
## Example ##
```shell
python go.py "/path/to/sitemap.txt" "http://www.google.com/" "/path/to/images/"
```
