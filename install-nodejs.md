### Install Node.js

##### Install using n Node version manager

Clone or download n node download manager: 
https://github.com/tj/n

In downloaded folder: 
<pre>
	$make install
</pre>

Install latest stable version with
<pre>
	n stable
</pre>

##### [Fix npm persmission issues](https://docs.npmjs.com/getting-started/fixing-npm-permissions)

Find path to npm's directory: 
<pre>
	npm config get prefix
</pre>

Change owner of npm's directories: 
<pre>
	sudo chown -R $(whoami) $(npm config get prefix)/{lib/node_modules,bin,share}
</pre>


