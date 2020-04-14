#  Monaco Redux

This is a fork of [monaco-port](https://github.com/MGageMorgan/monaco-port) that has been reworked to work with MediaWiki 1.31 and above. This fixes some deprecation issues and other bugs that affected versions above 1.30.

Live demo: https://computernewb.com/wiki/Main_Page?useskin=monaco

Note not everything works yet, and this is incomplete.

![alt-text](https://github.com/computernewb/monaco-redux/blob/master/screenshots/latest.png?raw=true 2)

## Installation
Clone this repository into your MediaWiki skins folder, and add the following 

### MediaWiki >= 1.25.0

```php
wfLoadSkin( 'monaco' );
```

### MediaWiki <= 1.24.0

On MediaWiki 1.24, the installation would work like this, but take note THIS IS NOT currently supported on MediaWiki 1.24 or below!

```php
require_once("$IP/skins/monaco/monaco.php");
```
## Screenshots
Zoomed-out images of the skin itself:
![alt-text](https://github.com/computernewb/monaco-redux/blob/master/screenshots/shot1.png?raw=true 1)
![alt-text](https://github.com/computernewb/monaco-redux/blob/master/screenshots/shot2.png?raw=true 3)