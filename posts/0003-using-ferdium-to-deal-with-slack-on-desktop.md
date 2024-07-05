# 3: Using Ferdium to deal with Slack on desktop

I have to use Slack for part of my volunteering life.  I have at least figured out a way to live
with Slack on desktop with [Ferdium](https://ferdium.org/).<!--more-->

Ferdium is open-source and has its code on [GitHub](https://github.com/ferdium/ferdium-app).  It
somehow uses [Ferdium recipes](https://github.com/ferdium/ferdium-recipes) for Ferdium to be a Swiss
Army knife of a desktop application.  Some services Ferdium supports include services I wouldn't use
due to native and first-party clients or better third-party clients, such as Bitwarden (which has
native clients) and Proton Mail (my uninformed opinion is that I trust ElectronMail as a Proton
Mail-specific application more with software security than Ferdium that is a catch-all client for
many services).

It would be interesting to get some of these services working, such as Snapchat, Discord, and
TikTok, but that's for another time.  (Also Discord and TikTok would probably work if I didn't use a
VPN for more than 95% of the time and Tor for the last 5% of the time.)

The full list of recipes can be browsed through on
[GitHub](https://github.com/ferdium/ferdium-recipes/tree/main/recipes).  (Sorry, there isn't a
better way to browse all available Ferdium recipes, as of July 2024.)

So, Ferdium works great with Slack.  On one hand, no one seems to be talking about using Ferdium as
an open-source client for Slack.  On the other hand, every other purpose-built open-source desktop
client for Slack seems to have stopped any development around 2020.  I know that Ferdium is, in very
rough terms, basically acting like a browser and letting users sign into Slack via that method.
However, Ferdium has let me use Slack more easily on desktop in a manner that is more bearable than
installing Slack's proprietary client from the AUR.  I would not be using Slack as much as I need to
without Ferdium -- I would rather unlock Ferdium with a local password than to have to explicitly
remember to use the "sign in with password" method when I log into Slack via browser.

(Except for very rare occasions, I almost use private browsing mode all the time so that I don't
stay signed in, so previously I used to log in and go through Slack's TOTP-based 2FA every time I
needed to check Slack.  Slack's e-mail notifications are also not very reliable and don't catch
everything that happens.)

Now, if we could just migrate from Slack to even hosted cloud [Zulip](https://zulip.com/) (that
would be free for registered nonprofits), then that would be really nice...

Also, there is no equivalent for Ferdium on Android yet.  (Ferdium can log into Zulip, but I'd
prefer to use the first-party Zulip for Zulip.)


