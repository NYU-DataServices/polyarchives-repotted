# polyarchives-repotted 🌱🍯

**see:** [nyu-dh/repotting-template](https://github.com/nyu-dh/repotting-template/)

**site name:** Poly Archives

**"old pot" url:** https://polyarchives.hosting.nyu.edu/

**"new pot" url:** TBD

**date repotted:**

wget \
 --recursive \
 --level 5 \
 --no-clobber \
 --page-requisites \
 --adjust-extension \
 --span-hosts \
 --convert-links \
 --domains polyarchives.hosting.nyu.edu \
 --no-parent \
 polyarchives.hosting.nyu.edu
