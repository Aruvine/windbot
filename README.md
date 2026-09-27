# windbot.app

Wind Bot's privacy policy and terms, which Discord requires to be reachable.

- https://windbot.app/ · https://windbot.app/privacy.html · https://windbot.app/terms.html

Static pages on GitHub Pages, so they stay up whether or not the bot is
running. Wind Bot's own code is in a private repository; nothing about it is
here but these three pages and a stylesheet.

## The domain

`CNAME` holds `windbot.app`, which is what tells GitHub Pages to answer for it.
Deleting that file takes the site off the domain, so leave it alone even though
it looks like a stray.

DNS at the registrar, pointing the apex at GitHub Pages:

    A     @     185.199.108.153
    A     @     185.199.109.153
    A     @     185.199.110.153
    A     @     185.199.111.153
    CNAME www   aruvine.github.io

`.app` is HSTS preloaded, meaning browsers refuse to load it over plain HTTP at
all. GitHub issues the certificate automatically once the DNS resolves, and
"Enforce HTTPS" is on.

Editing a page here is live within a minute of the push.
