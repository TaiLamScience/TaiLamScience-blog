# 4: SSO with SimpleLogin

Ever since Jitsi [required](https://jitsi.org/blog/authentication-on-meet-jit-si/) signing into an
account (from Google, Microsoft, or GitHub) in August 2023, things haven't been the same.<!--more-->

Techlore made a [video](https://www.youtube.com/watch?v=tMyB04Dq72A) about this situation when it
happened in 2023.

There was suggestion that Jitsi (or any relatively wide spread used service, for that matter) that
has never been capitalized on: [using SimpleLogin](https://simplelogin.io/developer/) as a
[single-sign on](https://en.wikipedia.org/wiki/Single_sign-on) (SSO) service.

Taking a look at its [documentation](https://simplelogin.io/docs/siwsl/intro/), this seems possible.
However, I don't have experience deploying server software like this; so I can't say for sure how
well this all works.  However, everything else from SimpleLogin seems to be solid, as its work
overall was good enough for Proton Tech to acquire SimpleLogin back in April 2022.

(Also SimpleLogin's documentation site needs to enable the option to change [the UI color
theme](https://github.com/mkdocs/mkdocs/wiki/MkDocs-Themes) from light to dark -- I know this is
possible for MkDocs in almost every other instance of MkDocs I've encountered.)

I'm really hoping more services allow SSO via SimpleLogin, as I'd be ok with signing into Jitsi with
SimpleLogin.

