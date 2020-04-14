# Let’s make your own blog using hexo :)

Every person has their own life,own thoughts,own experience in everyday.These experiences are very good to save for future.In programmering world this can be done by many people by their blog.

So,to make it easy today we are implementing a blog using hexo framework in node.js and host it in netlify with continuous development.So,let’s do it……..

First we need to know what is hexo and why it is unique?

Hexo is a fast, simple and powerful blog framework. You write posts in Markdown (or other markup languages) and Hexo generates static files with a beautiful theme in seconds.It is unique because we don’t need to generate the html file of each blog post of your own. We just need to change the markdown file of a blog post.

## So let’s learn how to do it…………….



### Prerequisite:
Node.js
NPM

Installation:
You can check this youtube video to install node and npm in your machine:
https://www.youtube.com/watch?v=qZQmCfkmbNA
Now the next part::: first open the terminal.Type the following command


``` $ npm install -g hexo-cli
```
This will finish the installation.
Create a blog:
Now to create a blog project in terminal type the following commands to initialize Hexo in the target <folder>.
```
$ hexo init <folder>
$ cd <folder>
$ npm install

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


_config.yml
Site configuration file. You can configure most settings here.
package.json
Application data. The EJS, Stylus and Markdown renderers are installed by default. If you want, you can uninstall them later.
scaffolds
Scaffold folder. When you create a new post, Hexo bases the new file on the scaffold.
source
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
$ hexo new [layout] <title>
```
Now you just need to edit the md file generated in the source folder.
To serve the post you can type:
```
$hexo generate
$hexo serve 
```
To check if it is asserted properly.
