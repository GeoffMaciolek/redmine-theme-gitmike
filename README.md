Redmine gitmike theme - Fork by GeoffMaciolek
## Warnings

This theme has had its stylesheed edited **directly**, rather than via the Sass->Compass (via Grunt) source.

Ergo this was done "wrong."  However,  I haven't been able to figure out how to do these things in the proper way yet, and I *really* wanted these fixes.  SASS editing

==============

This is github-like theme for Redmine.
It is based on A1 theme version 1.0.3 by Kirill Bezrukov www.redminecrm.com.

[screenshot1]: http://dl.dropbox.com/u/8932138/screenshot/gitmike/gitmike_2013-07-12_0706.png "gitmike screenshot"

![gitmike screenshot][screenshot1]

## Installation

1. Download from https://github.com/makotokw/redmine-theme-gitmike/tags
1. Move to `redmine/public/theme/gitmike`

Or by using git:

```
cd redmine/public/theme
git clone git://github.com/makotokw/redmine-theme-gitmike.git gitmike
```

### Change theme

Open redmine on a browser and go to Administration > Settings > Display > Theme.

## Development

```
cd redmine/public/theme
git clone git://github.com/makotokw/redmine-theme-gitmike.git gitmike
cd gitmike
gem install compass
npm install -g grunt-cli
npm install
grunt debug
```

## License

GPL3

## Todo

* Actually fix SASS rather than editing the (comiled) CSS
* Address spacing issues in project list 


## Change Log

* r8 2015/07/23: Theme changes (improperly) via direct CSS editing.
* r7 2014/04/05: Fixed some issues #12 #14 #17 #19 (from @rumpelsepp) #13 (from @timdp) #18 (from @cyberjunky)
* r6 2013/11/23: Dashboard (@n-rodriguez). Fixed some issues #6 #7 #8 and #10 reported from @statschner
* r5 2013/07/21: Improvement Forms
* r4 2013/07/12: Tested in Redmine 2.3. Updated to look like GitHub. Added assing_to and author column style on Issue Table when login user's one by @chocoby.
* r3 2013/01/16: Tested in Redmine 2.2. Added count style and changed priority-{#id} to priority-{position_name} on Issue Table.
* r2 2012/09/20: Removed Japanese font style in master branch, and added ja branch for Japanese.
* r1 2012/04/12: Supported Redmine 1.3.2
