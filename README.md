# Psirc 

A minimalist, responsive, and open-source theme for [Ghost](http://ghost.org) by [hiorws](http://hiorws.com).

Forked from [crisp](https://github.com/kathyqian/crisp-ghost-theme).

Lots of thanks!

### Required Steps for Installation

1. Download the files   
2. Replace the `example` disqus_shortname with your shortname on *line 4* of **partials/comments.hbs**, or delete the #comments div to remove comments altogether
3. Configure the follow buttons in **partials/follow.hbs** (see section below)
4. Add the folder to the **content/themes** directory of your Ghost installation
5. Select the theme in the settings page of your Ghost admin panel

### Suggested Customizations

* Change the link color on *line 87* in **assets/styles/crisp.css**
* Add code for Google Analytics in **default.hbs** after `{{ghost_foot}}`
* Remove irrelevant social sharing services in **partials/share.hbs**
* Change your blog logo to change the favicon and the picture in the sidebar (the blog cover is not used)

### Editing Follow Buttons

Crisp uses Font Awesome for icons. See the Font Awesome documentation for the [full list of icons](http://fortawesome.github.io/Font-Awesome/icons/) and [usage tips](http://fortawesome.github.io/Font-Awesome/examples/). 

I have placed some common buttons in **follow.hbs**, with more options in the commented out sections. Make sure to replace the `username` in the URLs so the links point to your profiles. 
