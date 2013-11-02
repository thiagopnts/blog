This blog's theme is a fork from [Balzac theme for jekyll](https://github.com/coletownsend/balzac-for-jekyll/)
I'm building my own on top of it.
 
``` bash
blog/
├── _includes
|    ├── footer.html  //site footer
|    ├── head.html  //site head
|    ├── head-dark.html  //dark site head for light pages
├── _layouts
|    ├── home.html  //homepage layout
|    ├── page.html  //page layout
|    ├── post-index.html  //post listing layout
|    └── post.html  //post layout
|    ├── post-no-feature.html  //feature image-less post layout
├── _posts
├── assets
|    ├── css  //preprocessed less styles. good idea to minify
|    ├── img  //images and graphics used in css and js
|    ├── js
|    |   ├── main.js  //jQuery plugins and settings
|    |   └── vendor  //all 3rd party scripts
|    └── sass 
├── images  //images for posts and pages
├── about.md  //about page
├── articles.md  //lists all posts from latest to oldest
└── index.md  //homepage. lists 5 most recent posts
```

