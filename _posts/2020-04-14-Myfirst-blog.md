<!----- Conversion time: 1.394 seconds.


Using this Markdown file:

1. Cut and paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β22
* Tue Apr 14 2020 02:07:13 GMT-0700 (PDT)
* Source doc: Let’s make your own blog using hexo :)
* Tables are currently converted to HTML tables.
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server.
----->


<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 0; ALERTS: 1.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>


Let’s make your own blog using hexo :)

Every person has their own life,own thoughts,own experience in everyday.These experiences are very good to save for future.In programmering world this can be done by many people by their blog.

So,to make it easy today we are implementing a blog using hexo framework in node.js and host it in netlify with continuous development.So,let’s do it……..

First we need to know what is hexo and why it is unique?

Hexo is a fast, simple and powerful blog framework. You write posts in[ Markdown](http://daringfireball.net/projects/markdown/) (or other markup languages) and Hexo generates static files with a beautiful theme in seconds.It is unique because we don’t need to generate the html file of each blog post of your own. We just need to change the markdown file of a blog post.

So let’s learn how to do it…………….



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/s-make0.png). Store image on your image server and adjust path/filename if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/s-make0.png "image_tooltip")


Prerequisite:



*   Node.js
*   NPM

Installation:



*   You can check this youtube video to install node and npm in your machine:

    [https://www.youtube.com/watch?v=qZQmCfkmbNA](https://www.youtube.com/watch?v=qZQmCfkmbNA)

*   Now the next part::: first open the terminal.Type the following command

    ``` $ npm install -g hexo-cli


    ```


This will finish the installation.

Create a blog:

Now to create a blog project in terminal type the following commands to initialize Hexo in the target &lt;folder>.

```


```
$ hexo init <folder>
$ cd <folder>
$ npm install
```
```


Once initialized, here’s what your project folder will look like:

.

├── _config.yml

├── package.json

├── scaffolds

├── source

|   ├── _drafts

|   └── _posts

└── themes


### **_config.yml**

Site[ configuration](https://hexo.io/docs/configuration) file. You can configure most settings here.


### **package.json**

Application data. The[ EJS](https://ejs.co/),[ Stylus](http://learnboost.github.io/stylus/) and[ Markdown](http://daringfireball.net/projects/markdown/) renderers are installed by default. If you want, you can uninstall them later.


### **scaffolds**

[Scaffold](https://hexo.io/docs/writing#Scaffolds) folder. When you create a new post, Hexo bases the new file on the scaffold.


### **source**

Source folder. This is where you put your site’s content. Hexo ignores hidden files and files or folders whose names are prefixed with _ (underscore) - except the _posts folder. Renderable files (e.g. Markdown, HTML) will be processed and put into the public folder, while other files will simply be copied.

Serve the blog locally:

To locally start the blog just type the following command:

``` 

$hexo serve

```

Now this will start the server locally in localhost:4000.

Create a new blog post:

To create a new blog post you just need to do a one command:

```

$ hexo new [layout] &lt;title>

```

Now you just need to edit the md file generated in the source folder.

To serve the post you can type:

```

$hexo generate

$hexo serve 

```

To check if it is asserted properly.


<!-- Docs to Markdown version 1.0β22 -->
