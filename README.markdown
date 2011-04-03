CMD
===

USAGE
-----

	Usage: cmd options

    OPTIONS:
   		--help, -h            Show this message
   		--version, -v         Show version
   		init                  Initialize cmd project
   		<commandname>         Run the specified command
   		edit <commandname>    Edit the specified command
   		rm <commandname>      Remove the specified command
   		ls                    List available commands


QUICK EXAMPLE
-------------

	$ cmd init
	$ ls
	cmdfiles
	$ cmd edit example
	echo "Hello"
	echo "From CMD!"
	$ cmd mkdir subdir
	$ cd subdir
	$ cmd ls
	example
	$ cmd example
	Hello
	From CMD
	$ cmd rm example

