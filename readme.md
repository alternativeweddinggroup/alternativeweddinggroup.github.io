# The Alternative Wedding Group Website
[http://thealternativeweddinggroup.co.uk](http://www.thealternativeweddinggroup.co.uk/)

## Description
Website to support the Alternative Wedding Group

## Dependencies

- Ruby
  - Jekyll
   - Kramdown
   - Sass

## Instructions

These instructions expect that you have Ruby already installed.

### Setup Development Area

```
jekyll serve
```

Visit the url [localhost:4000](http://localhost:4000/) to view the site.

### Deploy Build

#### Production

Each commit pushed to master will be deployed on the live site

## Documentation

During the Alpha/Beta stages, due to constant changes, documentation will be mainly written in-line. With a dedicated section being created at the first major release.

### File Structure

```
|- _site                 –  compiled development files (not committed)
|- web
|  |- _includes          –  partial snippets of code to be used
|  |                        in layouts
|  |- _layouts           –  page layouts
|  |- _posts             -  markdown files of news posts
|  |- media              -
|  |- static             -
|  |- {**/*.txt,html,md} -  files for website
|- _config.yml           -  Jekyll config file
|- readme.md
```

### Add a Service

To add a service to the site create a new file inside the `_services` directory called `[position-number]-name.md` eg, `0-service-name.md`.

Add the following to the top of the file:

```
---
title:
name:
heading:
image:
  heading:
  photo:
button:
  text:
  link:
---
```

## Report Issues

If you spot any issues please create a ticket via GitHub's Issue Tracker. If the issue is security related please use the contact information below.

## Contribute

In lieu of a formal style guide, take care to maintain the existing coding style.

## Contact

[hello@thealternativeweddinggroup.co.uk](mailto:hello@thealternativeweddinggroup.co.uk)

## License

The source is opened for educational purposes. No rights are assigned to any downloads or forks.

## Copyright

Unless otherwise stated all code and content remain copyright &copy; The Alternative Wedding Group. All rights reserved.
