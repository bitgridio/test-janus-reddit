# Example for generator-janus-dist

> This is an example of how to use the [generator-janus-reddit](https://github.com/sirkitree/generator-janus-reddit) generator for distributing links from a subreddit in [Janus VR](http://janusvr.com).

## Getting Started

### Understand Yeoman and this generator

A good place to start is the link above to the generator itself. It explains everything, including how to install it.

### Using this repository

This repository is intended to illustrate how to use this generator with a subreddit in order to generate the HTML and FireBox code necessary for placing the links from the subreddit into a Janus VR room.

You can visit this example within Janus itself at http://jeradbitner.com/test-janus-reddit/public/index.html.

Any questions, comments or improvements about the generator should be directed to the generator's issue queue at https://github.com/sirkitree/generator-janus-reddit/issues.

### How this was created

I simply ran the regenerator specifying the subreddit 'funny'.

The following is a list of command from start to finish to generate the `/public/index.html` file found in this repository.

1. `npm install -g generator-janus-reddit`
2. `yo janus-reddit`

I then entered `vrsites` when prompted and `50` for the number of posts to retrieve. That's it!
