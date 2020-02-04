
I experimented with image filters and recreate them by myself

* increase contrast
* generate an ISO effect
* increase/decrease brightness
* flatten image blacks
* make image look warmer/cooler

Most of the stuff I came up on my own, see inline comments of the functions
on details of how they exactly work.

Usage:

```
./abandoned-tuples \
  --contrast -20 \
  --iso 30 \
  --brightness -40 \
  --flatten 50 \
  --temperature +20 \
  cat.png test123.png

./abandoned-tuples -c 30 -i 30 -f 50 -b -30 -t +20 verkehrsmuseum_47964855892_o.jpg  out3.png
```

