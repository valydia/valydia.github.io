# This is my blog

### Pre-requisite

* Install [Jekyll][jekyll]
* [mdoc][]

[jekyll]: https://jekyllrb.com/docs/
[mdoc]: https://scalameta.org/mdoc/docs/installation.html

# Generate the source

```bash
coursier launch org.scalameta:mdoc_2.12:1.2.8 -- --site.VERSION 1.0.0 \
--out _posts
```

## Run locally 

>bundle exec jekyll serve

Browse [http://0.0.0.0:4000/][local-site]

[local-site]: http://0.0.0.0:4000