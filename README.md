# sass-starter
Base SASS architecture to help kickstart a project. Includes common JavaScript plugins.

## SASS compilation
Includes a bash script to watch and compile changes. This can be run as an alternative to a 'watch' declaration.

### 
    $ ./watch.sh

Is the equivalent of:

### 
    $ sass --watch sass/style.scss:css/style.css

## SASS setup

All variables and mixins should be housed inside the utils directory.

### 
    $ sass/utils/_variables.scss
    $ sass/utils/_mixins.scss

## JavaScript Plugins

- Box Sizing (border-box)
- RespondJs (Media query polyfill)
- jRespond (Breakpoint script manager)
- Modernizr 
- Safe Console Log