# Hugo Example: multilingual website

This example shows how you can create a multilingual website with http://gohugo.io/. This example was tested with version 0.13.

## How multilingual works

### content/{de, en}/ directories

If you want to translate a whole page copy the Markdown file into `content/de/` and `content/en/` directory.

## Run example

First you need to [install Hugo](http://gohugo.io/overview/installing/).

Then execute the following command in the repository's folder

	hugo server --buildDrafts -w

* Open http://localhost:1313/en/ to see the english version of the page.
* Open http://localhost:1313/de/ to see the german version of the page.

A language switcher is available in the upper-right.

## Build example

To create all the static stuff that you need to upload the website to your favorite hosting company run

	hugo --buildDrafts

You will find a newly created `public` directory.
