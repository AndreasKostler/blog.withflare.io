# Spline blog
To post, simply create a post in src/post and push. Lilac support github flavoured markup.

You don't need Lilac to do this but if you want to preview your post locally, install Lilac. For MacOS (assuming python is installed correctly) do the following:

1. `pip install virtualenv`
2. add virtualenv path to PATH or create a symbolic link to virtualenv in `/usr/bin` or any other location on your PATH
3. in `blog.withflare.io` do `. venv/bin/activate`
4. install Lilac with `pip install lilac`
5. create the scaffolding with `lilac deploy`
6. write, write, write
7. `make serve` will start a web server, preview your posts on `localhost:8888`

That's it. Now go and create.