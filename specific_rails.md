Each version of rails brings us exciting new features. But it also changes lots of things that we may want to keep using. Furthermore, if you are working on already mature system new version of rails can also bring compatibility issues. In such cases, you may want to keep using older versions of rails.

## How to use specific version of rails?
![install](https://user-images.githubusercontent.com/1642014/179756371-6a6a0d98-593f-4d04-9aa7-412b1707d055.PNG)

- While installing rails you can specify which version to install like this:

```ruby

gem install rails -v '6.1.6' 

```

- You can check installed version of rails like this:
![versions](https://user-images.githubusercontent.com/1642014/179756392-0b8a1973-e5ed-4391-ab6f-d866e3d3f378.PNG)

```ruby

gem list rails --local

```


>  ### But if I have multiple versions of rails installed, how rails know which version to create app?

- _When you create a new rails app, bundler automatically runs latest rails version that installed on your system. In order to specify which rails version that you want use, you should give it as a parameter while creating an app._
![appcreate](https://user-images.githubusercontent.com/1642014/179756406-2d254a03-90c1-46ba-9689-0dea14784de5.PNG)

```ruby

rails _6.1.6_ new my_app

```


- You can check your gemfile to verify version of rails.
![gemfile](https://user-images.githubusercontent.com/1642014/179756425-57297aaa-cdd8-499c-be1f-f58c9366a3d8.PNG)
