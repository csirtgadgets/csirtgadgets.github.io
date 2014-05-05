---
layout: default
---

## Quickstart 
```bash
$ ./configure --prefix=/opt/cif
$ make
$ make test
$ sudo make install
$ export $PATH=/opt/cif/bin:$PATH
$ /opt/cif/bin/cif-router -d
$ /opt/cif/bin/cif-smrt -R 0 -d
$ /opt/cif/bin/cif -d -q example.com
```

## Downloads
<a class='btn btn-primary btn-lg' href='{{ codeurl }}/releases'>Releases</a>
<a class='btn btn-primary btn-lg' href='{{ codeurl }}/tarball/master'>TAR File</a>
<a class='btn btn-primary btn-lg' href='{{ codeurl }}/zipball/master'>ZIP File</a>

## Authors and Contributors
@giovino, @jeffmurphy and @wesyoung

## Recent Posts
<ul class="posts">
    {% for post in site.posts limit:site.post_limit %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">[{{ post.category }}] {{ post.title }}</a></li>
    {% endfor %}
</ul>
