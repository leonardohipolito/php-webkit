Your PHP binaries will go here. If none are detected php-webkit will attempt to shell ```php-cgi``` in an attempt to run your application. You can additionally override the location in the ```package.json```.

You can find binaries for PHP at [PHP.net](http://php.net/) for most common platforms. The Windows distribution is simple and can be dropped in and ran with a properly configured ```php.ini```. Linux and Macs are trickier since repos and building from source put them in multiple directories. Users might find it easier to modify the packaged Linux and Mac binaries for [PHP Nightrain](https://github.com/naetech/nightrain) and get it to work without changes to the php-webkit source code.

In the future we hope to maintain and provide compatible PHP packages.