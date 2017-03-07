# HollyWordPress

#### ENVOYsites Gulp build system and boilerplate for WordPress.

## Requirements
**Node 6 recommended, tested on 6.9.5**

## Install
To get **holly** set up on your WordPress project, we recommend that Yarn package manager is installed on your machine. 
https://yarnpkg.com/en/docs/install

1. After Yarn is installed, open the terminal and `cd` to your project's **theme** directory and install **holly** for WordPress.

        yarn add envoy-holly-wordpress

2. After successful installation, a `gulpfile.js` should automatically be generated at your project's root directory. 

3. Initialize **holly** and answer a few prompts to scaffold starter boilerplate files. 

        gulp init

## Post-Install
After installing **holly**, the following entries should be added to the project's `.gitignore` file.

        /wp-content/themes/MY-THEME/dist
        /wp-content/themes/MY-THEME/node_modules

## Usage

* `gulp`

    Start **holly** in *development* mode. Styles and scripts will *not* be minified. Starts up "watch" task. 

* `gulp --prod`

    Start **holly** in *production* mode. Styles and scripts will be minified.
