Getting this running Heroku was suprisingly easy - they already have the required libraries.

To get it running locally, on a Mac with Homebrew:

```
brew install ghostscript
brew install imagemagick
```

Warning: Both of these take *forever* to install. (GhostScript is required for text)

Then to run it:

```
bundle install
./bin/shotgun
```

and visit [http://localhost:9393](http://localhost:9393)

Shotgun is like `rackup` but reloads on each request, so better for development.
