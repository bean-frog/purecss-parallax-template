# Pure CSS Parallax Slideshow Template
### Getting started:
- Make a Github account if you don't have one already. <br>
- Fork this repository<br>
- Set it up as a Github Pages site:<br>
  - In your forked repository, go to the settings tab <br>
  - Scroll and press "Pages" <br>
  - There should be a selector menu, with the title "Source". Set it to Github Actions. <br>
  - Just below there should be an option that says Jekyll, with a button that says "Configure". Press that. <br>
  - Theres gonna be some code and stuff, ignore it the default is fine. Press the green button that says "Start Commit" <br>
  - Ensure that "Commit directly to the main branch" is selected, and press Commit new file. <br>
- Navigate in your forked repository to "index.html", and look for lines that begin in <!-- and end in -->. these are comments, and they will tell you how to edit stuff and give clarifications.
- To change background images, go to style.css and wherever you see
```
#slideX:before {
  background-image: url("https://picsum.photos/1920/1080");
  and then some other stuff here
}
```
replace that url with the link to your image. The :before is only there on some, it doesn't matter if its there or not for changing the background

- every time you commit to your repository (save) it will automatically update your pages site which can be accessed at your-account-name.github.io/repository-name
  
### I'll probably make a generator sometime but for now just use this idk
  ### more info:
  - to change slides you can either scroll, use left/right arrows, or pageUp/pageDown keys.
  - Compatibility with KDE Connect has been added
  - Press F to fullscreen
