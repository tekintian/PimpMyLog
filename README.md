Pimp my Log 
===========

This is the dev branch.

## Install

- `npm install`
- `bower install`
- `composer install`

## Version

Change version in `package.json`, it will be automatically added in the `version.js` file on dev and build.

## Dev

- `grunt` to dev and watch : site available at `~/_site/_`
- `grunt build` to build for publishing and watch : site available at `~/_build/`
- `grunt build install-beta` to publish on the branch *beta*

## Production

- `grunt build install-production` to publish on the branch *master*
- then `grunt release` to update [demo.pimpmylog.com](http://demo.pimpmylog.com) then people will be alerted about a new version
