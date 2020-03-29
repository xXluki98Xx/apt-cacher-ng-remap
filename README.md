# apt-cacher-ng remap

## Overview
For more information read the post on [my blog page](http://blog.hudecof.net/posts/2014/08/15/apt-cacher-ng-and-remap.html).

It's about `repmap-...` configuration directive. Here you can find only the script part.

So here is the [Blog](https://web.archive.org/web/20180404031216/http://blog.hudecof.net/posts/2014/08/15/apt-cacher-ng-and-remap.html).

The Fedora Mirror lists doesnt list the update channels, so if you want to add them simple echo the url to the list like:

  echo "http://mirror2.hs-esslingen.de/fedora/linux/releases/31/Modular" >> /etc/apt-cacher-ng/mirror_list.d/list.fedora
  
  echo "http://mirror2.hs-esslingen.de/fedora/linux/updates/31/Everything" >> /etc/apt-cacher-ng/mirror_list.d/list.fedora
  
  echo "http://mirror2.hs-esslingen.de/fedora/linux/updates/31/Modular" >> /etc/apt-cacher-ng/mirror_list.d/list.fedora
