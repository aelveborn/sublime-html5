# Sublime HTML5

A Sublime Text 2/3 snippet to generate a HTML template.

## Install

### Option 1: Manual

Copy the files to your Packages directory.

### Option 2: Package Control

In the command pallette (Ctrl-Shift+P on Windows) type 'Add Repository' then press enter to add this repo: https://github.com/aelveborn/sublime-html5.git. Open command pallette again and type 'Install Package' Search for 'sublime-html5' then press enter to install.

## Usage

With a blank HTML file open, type

    htmlboiler

and press `TAB`.

That generates:

    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <title></title>
            <meta name="description" content="">
            <meta name="viewport" content="width=device-width, initial-scale=1">
        </head>
        <body>

            <p>Hello world!</p>

            <script src="//ajax.googleapis.com/ajax/libs/jquery/1.10.2/jquery.min.js"></script>
            <script>window.jQuery || document.write('<script src="js/vendor/jquery-1.10.2.min.js"><\/script>')</script>

        </body>
    </html>

## License 

[MIT Licensed](http://sloria.mit-license.org/).

## Forked from

[sloria](https://github.com/sloria/sublime-html5-boilerplate).