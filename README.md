### NematzNetwork Chat (NNC) - A hand-crafted IRC client based on Kiwi IRC
NematzNetwork Chat is a fully featured IRC client that can be extended to suit almost any needs.
Using the web application is extremly simple even without any IRC knowledge as all the common needs are built directly into the UI.

We forked Kiwi IRC to add the ability to communicate with the NematzNetwork Account Servers. You will not be able to access our servers, but we will create an API to connect to your servers. This is especaily useful if you want to tie in an IRC Nick with an account username, and other features in the account. We will also provide a way to link to a user's profile page, but there will be a setting to disable this.

### Installation

*Note: This requires Node.js to run. Make sure you have installed Node.js first! http://nodejs.org/download/*

1. Download the NNC source or clone the git repository:

    `$ git clone https://github.com/NematzNetwork/NematzNetworkChat.git && cd NematzNetworkChat`

2. Install the dependencies:

    `$ npm install`

3. Copy and edit the configuration file as needed:

    `$ cp config.example.js config.js`

    `$ nano config.js`

4.  Make sure the client code is built:

    `$ ./kiwi build`


### Running
From the source folder: `$ ./kiwi start`

You can also run NNC in the foreground to see any output by using the `-f` flag. Eg: `$ ./kiwi -f`

Open your new NNC instance in your browser. By default: http://localhost:7778/


### Bugs
Report bugs using the issue tracker on github: https://github.com/NematzNetwork/NematzNetworkChat/issues

### Licence
GNU Affero
http://www.gnu.org/licenses/agpl.html


### Thanks to
The Kiwi IRC Project, for whom this would not be possible.

The KiwiIRC logo credited to Michael Drahony (www.drahony.com)
