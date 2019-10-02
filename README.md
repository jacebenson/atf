# ATF

> Site about the scoped ATF application

## Installing / Getting started

To get up and running you need [hugo](https://github.com/gohugoio/hugo/releases).

```shell
git clone https://github.com/jacebenson/atf
cd atf
git checkout b docs
path/to/hugo server --watch #should bind to localhost:1313
```

The code above clones this repo, goes into the new directory
and then expects you to run `hugo server --watch`, which 
generates and serves the site locally.

### Deploying / Publishing

It appears there are ways to allow Github to host hugo sites, 
however, I've gone with Netlify to do this as that makes this really simple.  If you don't want to test locally, you can do that as well.

1.  Logon to [netlify](https://netlify.com)
2.  Add a new site from Github
3.  It should have a Build Command of `hugo`
4.  It should have a Publish Directory of `public`

## Contributing

If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome.

[Contributing Doc](https://github.com/jacebenson/atf/tree/docs/CONTRIBUTING.md)

## Links

- Site: https://atf.jace.pro
- Repository: https://github.com/jacebenson/atf/
- Issue tracker: https://github.com/jacebenson/atf/issues
  - In case of sensitive bugs like security vulnerabilities, please contact
    jace.benson@protonmail.com directly instead of using issue tracker. We value your effort
    to improve the security and privacy of this project!

## Licensing

"The code in this project is licensed under MIT license."
