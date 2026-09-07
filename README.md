# public-pages

Static pages shared by direct link only (GitHub Pages). No page in here is meant to be found by
browsing or search — each one lives under a random path, `robots.txt` disallows all crawlers, and
every page carries a `noindex` meta tag. That keeps it out of search results and off any listing,
but **anyone who browses this repo's file tree on github.com can still see the folder names** —
this is link-sharing obscurity, not access control. Don't put anything here that would be a real
problem if someone found it.

To add something new: make a new folder named with a random slug (`openssl rand -hex 8`), put an
`index.html` in it with a `noindex` meta tag, commit, push. Pages serves it at
`https://clarific-tech.github.io/public-pages/<slug>/`.
