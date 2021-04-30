# caldav for my personal calendar

`public/groupwareserver.php` is a copy (+ db configuration) of https://github.com/sabre-io/dav/blob/c1afdc7/examples/groupwareserver.php

## development

`docker-compose up`

## production deployment

Deploy

* `public` and
* `vendor`

to a web host pointing to `public`.

A database needs to be set up and configured according to the credentials mentioned in `public/groupwareserver.php`.

## Use

Connects to [davdroid/DAVx⁵](https://www.davx5.com/) ([APK via f-droid](https://f-droid.org/en/packages/at.bitfire.davdroid/)).

