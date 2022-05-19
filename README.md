# website
My personal website - with Prolog backend

## Requirements
The only thing required is the SWI-Prolog (*swipl*) interpreter.

## Usage
To start the webserver, simply call `./start.sh`. <br />
Stop the webserver, using `./stop.sh`.

Standard port is `8080`, so modify this in the [`start.sh`](https://github.com/memeToasty/website/blob/main/start.sh), if necessary.

If you are using windows, you may have to modify the [`start.sh`](https://github.com/memeToasty/website/blob/main/start.sh) to fit your binary.

## Plans
I intend to expand the Prolog backend to do something more interesting than just serving static files.
Currently there is no idea to what this would be, but if you have an idea for me, just let me know in the [Issues](https://github.com/memeToasty/website/issues)

## Credits
The source of the static Prolog server is [swipl-webapp-howto](https://github.com/roblaing/swipl-webapp-howto/tree/master/unit1)
