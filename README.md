## The [LAMurakami GitHub Pages](https://lamurakami.github.io) repository

On Saturday, May 30, 2020 after creating the repository and selecting one of the [Jekyll](https://jekyllrb.com/) Themes I used the [editor on GitHub](https://github.com/LAMurakami/lamurakami.github.io/edit/master/README.md) to update the README.md Markdown file for this new site.  I then linked it to [LAM Sites](http://sites.lam1.us).  I continued on with some of the [GitHub Pages documentation](https://help.github.com/categories/github-pages-basics) topics including Configuring a custom domain for your GitHub Pages site.

I initially found that Enforce HTTPS was Not yet available and then saw that a certificate for [github.lamurakami.com](https://github.lamurakami.com) good for 90 days was generated within minutes.  This made [github.lamurakami.com](https://github.lamurakami.com) my first website that does not use a self generated certificate that is automatically branded as untrusted by most browsers.

On Saturday, July 9, 2022 I decided to make github.lamurakami.com a redirect to lamurakami.github.io rather than a CNAME alias.  The Enforce HTTPS is mandatory for all github pages published to a github.io subdomain.  I noted that the subdomain is using a wildcard certificate that covers *.github.io *.github.com and more.  Had I not enabled a custom domain for the site and then specified Enforce HTTPS I would have noted the automated process to create Let's Encrypt certificates which led me to use Let's Encrypt certificates for all of my secure websites.

This README.md is no longer used to generate the index.html file with Jekyll Themes.
