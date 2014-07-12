## Static Website Demo

> This is a static site project template powered by [Gulp](http://gulpjs.com/),
> [Assemble](http://assemble.io/), [Handlebars](http://handlebarsjs.com/),
> [Bootstrap](http://getbootstrap.com/), [LESS](http://lesscss.org/),
> [BrowserSync](http://www.browsersync.io); and pre-configured for deployment to
> [Amazon S3](http://aws.amazon.com/s3/) / [CloudFront](http://aws.amazon.com/cloudfront/)
> ([CDN](http://en.wikipedia.org/wiki/Content_delivery_network) hosting).

Demo: http://d3kks39dujnhya.cloudfront.net/

#### Source

https://github.com/kriasoft/static-site-starter

#### Questions & Answers

* [How to deploy the site to GitHub Pages?](./docs/faq.md#how-to-deploy-the-site-to-github-pages)
* [How to deploy the site via SCP?](./docs/faq.md#how-to-deploy-the-site-via-scp)
* [How to securely store sensitive data in my public repository?](./docs/faq.md#how-to-securely-store-sensitive-data-in-my-public-repo)
* [Read more...](./docs/faq.md)

#### Blogs & Articles

 - [Static website on S3, CloudFront and Route 53, the right way!]
   (http://www.michaelgallego.fr/blog/2013/08/27/static-website-on-s3-cloudfront-and-route-53-the-right-way/)

#### How to Build

```
> gulp build    # or `gulp build --release`
```

#### How to Run

```
> gulp          # or `gulp --release`
```

This command builds the project, launches [browser-sync](http://www.browsersync.io)
development server and starts listening for modifications in source files.

#### How to Deploy

If [Travis CI](https://travis-ci.org/) is watching this repo, it will deploy
the site automatically after each commit. Otherwise, you may deploy it manually
by running:

```
> gulp deploy
```

#### Credits

 - Konstantin Tarkus -- [@koistya](https://twitter.com/koistya)

#### Support

Have questions or need help? Contact me via email [hello@tarkus.me](mailto:hello@tarkus.me)
or Skype: koistya.
