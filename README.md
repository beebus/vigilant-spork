# vigilant-spork

Install PM2
```
	$ sudo npm install -g pm2
```
Start server displaying the NodeJS file
```
	$ pm2 start helloWorld.js
```
OR
```
	$ node helloWorld.js
```
OR
```
	$ nodejs helloWorld.js
```

See rendered product:
[http://localhost:3000](http://localhost:3000)

Stop server
```
	$ pm2 stop helloWorld.js
```
OR Ctrl-C to terminate the node or nodejs servers.

Install NodeJS Locally:
1. Check if Node is already installed:
	`$ node --version`

2. If not installed, then proceed to install:
	[https://nodejs.org/en/download/]

	[https://github.com/nodesource/distributions/blob/master/README.md#installation-instructions]

To update NodeJS:
```
	$ sudo npm cache clean -f
	$ sudo npm install -g n
	$ sudo n stable
```

Clone the Repo:
1. Navigate in terminal to parent folder of the directory you want to be working in.
2. `$ git clone https://github.com/beebus/vigilant-spork.git`
		(this sets up the local copy of the code)

IDE: WebStorm by JetBrains


[https://github.com/nodesource/distributions/blob/master/README.md#installation-instructions]