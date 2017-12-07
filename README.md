This is a sample Nikola blog, compatible with Netlify CMS.

Hit this one button:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/getnikola/nikola-netlify-cms&scheme=cms)

And then configure it in Netlify’s panel. Go to the *Identity* section of *Settings*, and:

1. Enable Identity service
2. Set it to *Invite only*
3. Enable social login (or not) — GitHub would be nice
4. Enable Git Gateway (at the bottom)
5. Add users on the Identity *tab* (top of the page) if necessary.

Also, consider changing your site name in the General settings, and site URL in `files/admin/config.yml`. You should end up with a site with the Netlify CMS available in `/admin/`. Congratulations!

*PS.* Netlify CMS can be used without Netlify’s CDN/hosting service, but that requires some extra configuration work.  Also, *preview images* require theme support (not available in the default).
