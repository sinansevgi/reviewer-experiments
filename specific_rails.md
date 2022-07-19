Each version of rails brings us exciting new features. But it also changes lots of things that we may want to keep using. Furthermore, if you are working on already mature system new version of rails can also bring compatibility issues. In such cases, you may want to keep using older versions of rails.

## How to use specific version of rails?

While installing rails you can specify which version to install like this:

```ruby

gem install rails -v '6.1.6' 

```

You can check installed version of rails like this:

```ruby

gem list rails --local

```


>  ### But if I have multiple versions of rails installed, how rails know which version to create app?

_When you create a new rails app, bundler automatically runs latest rails version that installed on your system. In order to specify which rails version that you want use, you should give it as a parameter while creating an app._

```ruby

rails _6.1.6_ new my_app

```

You can check your gemfile to verify version of rails.
