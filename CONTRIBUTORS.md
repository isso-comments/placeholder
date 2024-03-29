# Contributions to Isso

## Creator & Maintainer

* Martin Zimmermann <info@posativ.org>

## Co-Maintainers

* Benoît Latinier @blatinier <benoit@latinier.fr>

* Jelmer Vernooĳ <jelmer@jelmer.uk>

## Contributors

In chronological order:

* Florian Baumann <flo@noqqe.de>
  * Documentation fixes in the early days

* Federico Ceratto <federico.ceratto@gmail.com>
  * Support for ipaddr
  * Added a sample configuration file

* Sploinga <xavier@sploing.be>
  * French translation

* Laurent Arnoud <laurent@spkdev.net>
  * Make Isso not accept blank comments

* Chimo <chimo@chromic.org>
  * STARTTLS for SMTP notifications

* Jocelyn Delande <jocelyn at delalande dot fr>
  * Documentation for comment counter and API
  * Default SMTP security to STARTTLS

* Srijan Choudhary <srijan4@gmail.com>
  * Correct nginx examples in documentation
  * Added comment pagination feature
  * Provide a demo site

* William Dorffer <schoewilliam@gmail.com>
  * Convert SCSS to plain CSS
  * Refresh style, make it responsive

* Baptiste Darthenay
  * Esperanto translation

* Matías Ducasa <https://github.com/matiasducasa>
  * Spanish translation

* Daniel Gräber <https://github.com/albohlabs>
  * Added ansible for provisioning

* Nick Hu <https://github.com/NickHu>
  * Added configuration to require email addresses (no validation)
  * Fix Vagrantfile

* Benoît Latinier @blatinier <benoit@latinier.fr>
  * Fix thread discovery
  * Added mandatory author
  * Added admin interface

* Ivan Pantic <ivanpantic82@gmail.com>
  * Added vote levels

* Martin Schenck @schemar
  * Improvement in the german translation

* @cclauss
  * Pep8 and drop of legacy supports (old python & debian version tested in travis)
  * Make travis use pyflakes

* Lucas Cimon @Lucas-C
  * Added the possibility to define CORS origins through ISSO_CORS_ORIGIN environment variable
  * Fix a bug with <a> in <svg>
  * Fixing likes counter of replies not being displayed
  * Adding contrib/dump_comments.py
  * Adding a [server] proxy-fix-enable-x-prefix configuration option
  * Using .access_route instead of .remote_addr to take into account HTTP_X_FORWARDED_FOR header

* Yuchen Pei @ycpei
  * Fix link in moderation emails when isso is installed in a sub URL

* @Rocket1184
  * Fix typo in CJK translations

* @vincentbernat
  * Added documentation about data-isso-id attribute (overriding the standard isso-thread-id)
  * Added multi-staged Dockerfile
  * Added atom feed
  * Added a nofollow/noopener on links inside comments to protect against bots
  * Added a preview using the existing preview endpoint

* @p-vitt & @M4a1x
  * Documentation on troubleshooting for uberspace users

* Facundo Batista <facundo@taniquetil.com.ar>
  * Added a generic way to migrate from a json file

* @benjhess
  * Optionnal gravatar support

* Steffen Prince @sprin
  * Upgrade to Misaka 2

* Rocka <i@rocka.me>
  * Implementation and documentation about async comment loading

* Pelle Nilsson @pellenilsson
  * Reply notifications

* Craig P Hicks @craigphicks
  * Fix sub urls configurations on admin interface

* Chris Warrick @Kwpolska
  * Update Polish translation
  * Redirect to comment after moderation

* fliiiix <l33t.name>
  * Import disqus posts without Email
  * Import disqus post without IP
  * Fixing minor code inconsistencies
  * Testing for moderation and unsubscribe

* [Your name or handle] <[email or website]>
  * [Brief summary of your changes]
