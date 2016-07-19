# APEX Client Extension - ACE

**Clone and run for a quick way to see the ACE Browser in action.**

This is a configurable Browser based on the awesome [Electron](http://electron.atom.io). It adds several client-features to your Oracle APEX application.

All you need to change is the `features.json` file, where you define which features should be enabled in your APEX application:

- access to the clipboard
- definition of global keyboard shortcuts
- window level menues
- read/write files on the client
- desktop notifications
- run shell scripts on client
- many more to come


## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/FOEXgmbh/apex-client-extension
# Go into the repository
cd apex-client-extension
# Install dependencies and run the app
npm install && npm start
```

Learn more about ACE and its API in the [documentation](doc/doc.md).

#### License: [MIT](LICENSE.md)
