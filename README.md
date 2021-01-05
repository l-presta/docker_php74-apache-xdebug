# PHP 7.4 w/Apache and XDebug in Docker (batteries included)

1. Clone this repo
2. Create an alias to loopback network interface `sudo ifconfig lo0 alias 10.254.254.254`
3. Start the container with `docker-compose up --build`

...and you're ready to go! 

Now you can set a breakpoint in `code/index.php` script and Listen to XDebug (**VSCode configuration included**): open up your browser on localhost and your code should be stopped on your breakpoint 😉