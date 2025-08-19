
# What

A simple shell script to disply a random kitten. Also, an example for packaging with Flox.

# Why? 

  * Because I wanted to show how package a script using `flox build` to invoke a manifest package build.
  * Because kittens are cute and sometimes you just need a little cuteness in your life.

# How

Activate this enviornment with `flox activate` and then see a kitten. This activation will ensure all dependencies are needed. In this eample, we rely upon `curl`, `imgcat`, and `bash` to make this happen. Think of these dependencies as "what you need with an empty hard disk?", as we're want no implicit dependencies.

You can run `kittentime` from this directory and see a kitten.

# Build a package


`flox build`

# Publish this package to your catalog


`flox publish`


# Install this package into a Flox env

`flox install ${your_floxhub_username}/kittentime`

# License

No right reserverd. Do whatever you want with this code, but please don't sue
me if it breaks something or causes any issues. Use at your own risk!

