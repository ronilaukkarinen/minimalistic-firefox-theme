## Minimalistic Firefox userChrome.css tweak/theme for OS X

[CustomCSSforFX](https://github.com/Aris-t2/CustomCSSforFx) has a good tutorial on how to tweak Firefox with pure CSS only. This is my "theme" for Firefox Developer Edition. By enabling, you will be able to get Firefox to look like this:

**Tested:** [Firefox Quantum: Developer Edition](https://www.mozilla.org/en-US/firefox/developer/), Firefox 58.0b1 (64-bit)

### Installation

1. Go to Library/Application Support/Firefox, find your profile folder and create folder "chrome" (lowercase) under it
2. Create userChrome.css file to that folder and paste contents of [userChrome.css](https://github.com/ronilaukkarinen/minimalistic-firefox-theme/blob/master/userChrome.css) or [userChrome-safaristyle.css](https://github.com/ronilaukkarinen/minimalistic-firefox-theme/blob/master/userChrome-safaristyle.css) if you prefer Safari UI
3. Restart Firefox
4. **Note:** If you use dark theme or FirefoxDeveloperEdition, you should change the base theme to Light first (**Tools** > **Add-ons** > *Themes*).

More tweaking tips in [CustomCSSforFX](https://github.com/Aris-t2/CustomCSSforFx) repository.

![Screenshot](https://rolle.wtf/ff-safari.png "Screenshot")
Screenshot of Safari styled Firefox 58.