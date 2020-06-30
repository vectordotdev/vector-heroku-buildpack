This is a component of our [**Heroku Button**](https://devcenter.heroku.com/articles/heroku-button) support.

### Why does this exist?

Heroku doesn't normally deal much with binaries, so the best way for us to provision Vector onto a machine is to have it in a buildpack which can fetch and provision the binary to a known location, as well as do any prefetching of, say, a configuration from a URL.

### Can I use this?

Of course! Add this buildpack to your `app.json`!

If you want to have a `vector` command available in your Heroku deployment for some other reason, well, have at!