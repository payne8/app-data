## App Data Folder

A simple library that makes it easy to get the Application Data folder for the current operating system.

# Usage

```bash
npm install app-data-folder
```

```javascript
let appData = require('app-data-folder');
let applicationName = 'Storm';
let appDataPath = appData(applicationName); // returns a platform specific path to the default location for application data

// e.g.
// Windows: C:\\Users\\<User Name>\\AppData\\Roaming\\<application name>
// MacOS: /Users/<User Name>/Library/Application Support/<application name>
// linux: /home/<User Name>/.<application name>
```

I cringe at the thought of copying this code into each one of my apps. So I made it into a reusable library. Maybe a bit overkill but it makes me sleep better.

Check out some of my bigger projects at https://www.stormfolder.com
