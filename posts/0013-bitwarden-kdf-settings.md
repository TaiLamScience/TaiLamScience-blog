# 13: Bitwarden KDF settings

There was a [guide](https://artemislena.eu/posts/2023/04/bitwarden-kdf.html) from early 2023 on what to change in the default [KDF](https://en.wikipedia.org/wiki/Key_derivation_function) settings of [Bitwarden](https://en.wikipedia.org/wiki/Bitwarden).<!--more-->

(The guide has been saved on the [Wayback Machine](https://web.archive.org/web/20240915133321/https://artemislena.eu/posts/2023/04/bitwarden-kdf.html) and [archive&period;today](https://archive.is/ze8IL).)

You must log in via browser to edit these settings.  (Neither the desktop apps nor the mobile apps can change the following settings.)

1.  From the main screen in Bitwarden, navigate through the following menus: Security (vertical menu) > Keys (horizontal)
2.  Select `Argon2id` for "KDF algorithm" and enter `10` for "KDF iterations".
3.  Enter 64 for "KDF memory (MB)" and 8 for "KDF parallelism" (number of threads).
4.  If you changed any settings, then click on the "Change KDF" button to save any changes (and Bitwarden will log you out of your account on all devices).
    * Otherwise, if no changes were made, then you can leave the "Keys" menu.

## Personal context

I need to make sure I have something I can reference when I set up organization accounts on Bitwarden for colleagues and friends.

I vaguely remember that this was discussed roughly around the same about how the default KDF for LUKS (full disk encryption on Linux) was set up.  Back in April-May 2023, the [sources](https://sr.weblog.lol/2023/05/sr132) for [episode 132](https://www.youtube.com/watch?v=U-YeDGfINXs) of the the _Surveillance Report_ [podcast](https://sr.omg.lol/) was released during the time when the podcast released roughly biweekly - so the podcast lagged at least 1-2 weeks behind current events.

This forum [thread](https://mjg59.dreamwidth.org/66429.html) helped to date this news story, as well as this [assessment](https://dys2p.com/en/2023-05-luks-security.html).
