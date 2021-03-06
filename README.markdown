[![endorse](http://api.coderwall.com/robertkowalski/endorse.png)](http://coderwall.com/robertkowalski)

Coderwall for Octopress
=======================

Adds your coderwall.com badges to the octopress sidebar

 * triggered by entering a username for coderwall in _config.yml
 * badges linking to the coderwall profile
 * uses the in octopress available ender.js (bonzo / qwery)
 * or the new jQuery (since Octopress 2.1)


Installation
------------

 - Copy the files to your octopress rootfolder (don't forget the hidden files)

 - Add ```asides/coderwall.html``` to the ```default_asides``` or ```default_asides``` ```post_asides``` or ```page_asides``` in the ```_config.yml```

Example:

```
default_asides: [asides/recent_posts.html, asides/github.html, asides/twitter.html, asides/delicious.html, asides/pinboard.html, asides/googleplus.html, asides/coderwall.html]
```

 - Additionally, add to your ```_config.yml```:

```
coderwall_user: YOUR_USERNAME
```

![Sidebar](http://robertkowalski.github.com/octopress-coderwall/sidebar.png)

---------------------------------------


License
-------

Copyright (c) 2012, Robert Kowalski

All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.


THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

