# make.vic.blue

URL that redirects phones and tablets to respective app store page, other devices
get redirected to http://vic.blue

## How to deploy

    $ cd html
    $ s3cmd sync . s3://make.vic.blue/
