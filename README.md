With clean URLs turned on in Jekyll, there can be a conflict between page names and filepaths that share the same name.

Demo: http://bryanschuetz.github.io/jekyll-directory-page-conflict

Requests to /about should be served /about.html

Because there is also an /about/about-page.html requests for /about are served a 404 error on GitHub Pages and are served a directory index in WEBrick when running a server locally.
