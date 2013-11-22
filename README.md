ChromeADB
=========

**ChromeADB** is the Chrome ADB(Android Debug Bridge) Client.

When launched, you can see all devices connected to your machine if the ADB connection is successful.  
Click a device that you want to control or monitor. And enjoy!

![screenshot](https://lh3.googleusercontent.com/-YZShQkbkFCQ/Uo-kcYDhn2I/AAAAAAAAFPo/G2aeDR4jLZY/w792-h532-no/chromeadb.png)



How to install
--------------

- Install [node.js][0]
- `$ npm install -g bower`
- `$ bower install angular bootstrap`
- Open `chrome://extensions` in your Chrome.
- Check `Developer mode`
- Select `Load unpacked extensions...`
- Open `$CHROMEADB_HOME/src`



How to build
------------

- `$ npm install -g grunt-cli`
- `$ npm install`
- `$ grunt`
- Check a zip file in `$CHROMEADB_HOME/package`



How to use
----------

### Pre-requirements

- ADB included in [Android SDK][1]
- Start ADB daemon
	- `$ adb start-server`
- Launch **ChromeADB**

No description needed anymore :)



License
-------

BSD 2-Clause. See the `LICENSE` file.




[0]: http://www.nodejs.org/ "node.js"
[1]: http://developer.android.com/sdk/index.html "android sdk"
