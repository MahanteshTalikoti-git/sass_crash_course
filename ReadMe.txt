npm i -g sass
sass --watch scss/style.scss css/style.css

Note: ter is vs code extension called Live Sass Compiler.
If above ext is installed, at bottom panel there will be watch sass btn.

_config.css -> is a technique to move all the constants to such a file.
if _ (under score) is used, it will not create any separate css file post compilation.

cd .\flexbox-crashcourse\
cd . > index.html
cd . > style.css
code .\index.html

Valuable short cut:
div.item*3{Item $}

GitHub Pages:
Note: make sure main html file is always called "index.html"
After code push, Navigate to Settings - Pages.
Under Build and deployment, choose source as Deploy from a branch
Branch: master
Click on Save 

Below msg will be displayed:
Your GitHub Pages site is currently being built from the master branch.

Generated URL: https://mahanteshtalikoti-git.github.io/sass_crash_course/
