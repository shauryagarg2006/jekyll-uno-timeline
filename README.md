# Jekyll-Uno with Projects as Timeline
A Jekyll Theme, based on the Uno-Theme with a list of projects as Timeline.

## How to build and serve

```
docker run --rm \
  -p 4000:4000 \
  --volume="$PWD:/srv/jekyll" \
  -it jekyll/builder \
  jekyll serve && jekyll serve
```