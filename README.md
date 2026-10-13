# SocialSpec

A Micro.blog plug-in that adds [SocialSpec](https://socialspec.org/) discovery
files to a site:

- `/.well-known/contact.vcf` contains the site author’s full name and, when
  configured, email address.
- `/.well-known/about.md` contains the raw Markdown from the site’s `/about/`
  page.

The files are generated with Hugo resources from the included
`socialspec-plugin.html` partial.

The plug-in adds an **Email** setting under `params.socialspec_email`.
