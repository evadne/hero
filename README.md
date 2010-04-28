#	`hero.rb`

`hero.rb` swizzles Heroku credentials and shows the currently used one if no argument has been specified.  This script derives from Aeonscope’s [Managing Multiple Heroku Accounts](http://www.aeonscope.net/2010/02/22/managing-multiple-heroku-accounts).





##	Assumptions

You have `me@example.org.herokuCredential` in `~/.heroku`.





##	Usage

	$ hero
	Heroku credentials not found.
	
	$ hero ev@monoceroi.com
	
	$ hero
	Operating under ev@monoceroi.com.





##	Installation

*	Clone the repository

*	Make the script executable

		$ chmod +x hero.rb

*	Add the repository’s directory to your Bash path within `$BASH_SOURCE`:
	
		export PATH="~/PATH_TO_REPOSITORY/:$PATH";




