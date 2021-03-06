# TAL Page Templates for ownCloud

| Code quality | Latest release |
|--------------|----------------|
| [![Scrutinizer Quality Score](https://scrutinizer-ci.com/g/tanghus/tal/badges/quality-score.png?s=434867c2ea156fc326b5b6a306bfa5e35b844e50)](https://scrutinizer-ci.com/g/tanghus/tal/) | [![Latest release](http://img.shields.io/github/release/tanghus/journal.svg)](https://github.com/tanghus/tal/releases) |

Develop using the Template Attribute Language instead of having clumsy
`<?php echo $var; ?>` tags in your markup.

Read more at the [PHPTAL site](http://phptal.org/introduction.html)

## Install from git

1. Go to your ownCloud apps dir and clone the repo there:
	 <pre>
	 cd owncloud/apps
	 git clone git://github.com/tanghus/tal.git
	 </pre>

2. go to the newly created `tal` folder and update the [PHPTAL](https://github.com/pornel/PHPTAL) submodule:

	 <pre>
	cd tal
	git submodule update --init
	 </pre>

3. From your browser go to the ownCloud apps page (`/index.php/settings/apps`) and enable the "TAL Page Templates for ownCloud" app.

4. Go to the Admin page (`/index.php/settings/admin`) and check if the installation has succeeded. You will find a section with a link to the manual.

