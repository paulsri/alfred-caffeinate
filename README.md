# alfred-caffeinate
Prevent macOS from Sleeping

## deps

1. Install [Alfred](https://www.alfredapp.com).

2. Ensure `caffeinate` is in your `$PATH`, by running:

        $ which caffeinate
        /usr/bin/caffeinate

## setup and configuration

1. Import the Alfred [alfred-caffeinate](https://github.com/paulsri/alfred-caffeinate/blob/master/Caffeinate.alfredworkflow) workflow by double-clicking the workflow file after downloading it.

1. The default caffeination time is 1 hour (3600 seconds), but feel free to change this in in `alfred-caffeinate.sh` at *line 4*. 

        # default caffeination time in seconds
        default_caffeination=3600

## usage

In Alfred type the following:

To caffeinate (default time of 1 hour):

        caffeine
        
To caffeinate 8 hours:

        caffeine 8

To resume normal sleep behavior:

        caffeine off
        
## thanks

Many thanks to the [stack overflow](http://stackoverflow.com) community for lots of shell scripting help!

## screenshots of alfred and notifications

<img src="https://raw.githubusercontent.com/paulsri/alfred-caffeinate/master/images/alfred-caffeine8.png" width=600>
<img src="https://raw.githubusercontent.com/paulsri/alfred-caffeinate/master/images/alfred-caffeineoff.png" width=600>
<img src="https://raw.githubusercontent.com/paulsri/alfred-caffeinate/master/images/notify-caffeine8.png" width=350>
<img src="https://raw.githubusercontent.com/paulsri/alfred-caffeinate/master/images/notify-disablecaffeine.png" width=350>
<img src="https://raw.githubusercontent.com/paulsri/alfred-caffeinate/master/images/notify-notcaffeinated.png" width=350>
<img src="https://raw.githubusercontent.com/paulsri/alfred-caffeinate/master/images/notify-already.png" width=350>
