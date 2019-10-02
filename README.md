## Site is using Hugo modules

* Be sure to have a [resent version](https://golang.org/dl/) of **golang** installed



## Build command

- If dependencies is not installed then first run

> npm install

- Build command

> npm start



## Update to newer version of Hugo module

There are 2 Hugo modules installed

* github.com/MunifTanjim/minimo
* github.com/craftsmandigital/content/hugo-minimo

Here are the commands

> hugo mod get github.com/MunifTanjim/minimo
>
> hugo mod get github.com/craftsmandigital/content/hugo-minimo

Another way to update to latest version of all modules, is to delete the files `go.mod` and `go.sum`. Then run this command:

> hugo mod init

Head over to the [documentation](https://gohugo.io/commands/hugo_mod/) for more about the `hugo mod` commands



