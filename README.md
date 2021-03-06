generate-modman
===============
Automatically generate modman file for Magento 1 modules on the fly.

Requirements
------------
- Mac or Linux based OS
- awk


Download
--------

    curl -sS https://raw.githubusercontent.com/mhauri/generate-modman/master/generate-modman > generate-modman

Move file to /usr/local/bin

    sudo mv generate-modman /usr/local/bin

Make the file executable
    
    sudo chmod 755 /usr/local/bin/generate-modman
    

Composer Install
--------
Alternative to manual download: Install via composer: generate-modman/generate-modman


Usage
-----

    generate-modman [options]


Options
-------
    --include-others            Include non default magento directories
    --include-others-files      Include non default magento directories as files
    --include-others-files-mindepth=MINDEPTH    mindepth for include other files. (default: 1 to skip root)
    --include-app-code-core     Include app/code/core files (e.g. for official patches)
    --subdirectory=DIRNAME      If files are in a subdirectory of the module (e.g. src for src/app/code/community))

License
-------

generate-modman is licensed under the MIT License - see the LICENSE file for details
