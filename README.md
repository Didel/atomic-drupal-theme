## Installation
To install all required dependencies, you will need to do these things:
- Run `npm install` from within this theme directory
- Install and enable the [Component Libraries](https://www.drupal.org/project/components) module.
  After it is enabled, no further configuration of the module is required.
- Enable the theme and set it as the active Drupal theme. 

## Build the theme
Once that is done, you can run the following commands (all from within the theme)
directory:

- `npm run stylesheets` to compile all the stylesheets into dist/style.css
- `npm run styleguide` to build a styleguide in ./styleguide
- `npm run build` to do both of the above.
