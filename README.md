# hugosite
The source code for the [website](https://www.calculateTHIS.xyz)

## Usage

To use this to build a site, first you can test it's working with

```
$ hugo serve
```

and the site should be running at `localhost:1313`. If it is, you are good
to go. If not, open up an issue. It probably needs a bit more than that, like
static files and the theme properly done through `hugo mod`.

### Adding content

To add content use

```
$ hugo new content content/blog/blog1.md
```

### Building

After you run the site and it looks good, you can build it with
