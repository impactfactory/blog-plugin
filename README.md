# blog-plugin
A simple unfinished blog plugin as alternative to the Rainlab Blog Plugin.

As a generalist I was overwhelmed to always understand the code of the Rainlab Plugin and lost a lot of time. At some point I decided that I'm probably faster with just setting up my own 3 models :), so I could add fields and templating easier.

- - - - - - -
DEPENDENCIES

- Bootstrap 5 (mainly for cards, image overlay keyvisual, badges, typography and grid)
- jQuery for languageswitcher
- impactfactory.team (unpublished / just for displaying an author (could be replaced with user plugin or backend user relation (?)).
- rainlab.translate
- offline.sitesearch 
- abwebdevelopers.oc-imageresize-plugin
- inetis.list-switch



- - - - - - -
FEATURES SO FAR

- post list view ()
- detail view
- posts in categories list view
- posts with tags list view 
( all of them with Masonry and Bootstrap cards, with title, text, keyvisual, metas and seo fields)
- tag cloud snippet
- post types for templating different views and cards (f.e. video posts, gallery posts, texts posts)

<br>

- responsive keyvisual (keyvisual not in the background) with webp and resolution check
- fast, Lighthouse tests at 90s
- css for user added pictures in articles is ready and works
- tags have different css according how they are used

<br>

- multilanguage in front and backend (de and en already translated)
- multilanguage breadcrumb and blogposting rich snippets json code
- multilanguage metas
- language switcher
- sluggable (all multilanguage and alternative links work)
- field for adding keywords for work around of search plugin (which is not really multilanguage)

<br>

- searchable (every model, multilanguage work around fields)

<br>

- rights management for every model
- flexible edit status for editors overview when to read proof, translate and publish etc
- easy to set up keyword based multilanguage landing pages :)
- all in froala editor (use each of your snippets in posts, categirues and tags list :)
- publish directly in list view
- time to read field

<br>

- old jQuery of OC replaced by newer version to handel the Lighthouse security issue

<br>

- - - - - - -
WISH LIST

- time to read automated (as in the plugin that exists)
- related posts
- most read posts
- automatic multilanguage registration of item types for sitemap plugin (with individual priority field / for posts details, post list, tag lists and category lists)
- imageresizer cropping for keyvisual not only centered, but adjustable trough user, depending on hwo the keyvisual picture is)
- real multilanguage search plugin...
- ability for editors to add pictures that fulfill requirements of Lighthouse (with and height attributes, resolution 2x option, webp transformation is browser can do it)

<br>

- - - - - - -
THANX TO

- munxar for teaching me!
- Rainlab and October Founders and Maintainers
- Laravel, Twig, css, jQuery communities











