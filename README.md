# GitLab and GitHub public Projects/Repositories
The
[gitlab.com/LAMurakami/lamurakami.gitlab.io](https://gitlab.com/LAMurakami/lamurakami.gitlab.io)
Project is a clone of the
[github.com/LAMurakami/lamurakami.github.io](https://github.com/LAMurakami/lamurakami.github.io)
Repostory.  My
[gitlab.com/LAMurakami](https://gitlab.com/LAMurakami)
account was created so that Projects can be cloned using https without
authentication over IPv6 as well as IPv4 unlike the
[github.com/LAMurakami](https://github.com/LAMurakami)
Repostories that can only be accessed over IPv6 with the
[IPv6 only workaround.](https://lamurakami.github.io/blog/2024/06/05/Access-GitHub-com-from-an-instance-without-a-public-IPv4-address.html)

## The LAMurakami [GitLab](https://lamurakami.gitlab.io)/[GitHub](https://lamurakami.github.io)  Pages [Project](https://gitlab.com/LAMurakami/lamurakami.gitlab.io)/[Repository](https://github.com/LAMurakami/lamurakami.github.io)

On Saturday, May 30, 2020 after creating the repository and selecting one of the [Jekyll](https://jekyllrb.com/) Themes I used the [editor on GitHub](https://github.com/LAMurakami/lamurakami.github.io/edit/master/README.md) to update the README.md Markdown file for this new site.  I then linked it to [LAM Sites](http://sites.lam1.us).  I continued on with some of the [GitHub Pages documentation](https://help.github.com/categories/github-pages-basics) topics including Configuring a custom domain for your GitHub Pages site.

I initially found that Enforce HTTPS was Not yet available and then saw that a certificate for [github.lamurakami.com](http://github.lamurakami.com) good for 90 days was generated within minutes.  This made [github.lamurakami.com](http://github.lamurakami.com) my first website that does not use a self generated certificate that is automatically branded as untrusted by most browsers.

On Saturday, July 9, 2022 I decided to make github.lamurakami.com a redirect to lamurakami.github.io rather than a CNAME alias.  The Enforce HTTPS is mandatory for all github pages published to a github.io subdomain.  I noted that the subdomain is using a wildcard certificate that covers *.github.io *.github.com and more.  Had I not enabled a custom domain for the site and then specified Enforce HTTPS I would have noted the automated process to create Let's Encrypt certificates which led me to use Let's Encrypt certificates for all of my secure websites.

This README.md is no longer used to generate the index.html file with Jekyll Themes.
