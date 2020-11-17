# No Longer Updated!

Reason: Discord caches its images for 1 year. This means that any new shiny Pokemon images (changed after the current, non-shiny is loaded) will not work for user display.

I have changed my approach and made a new git for this. See https://github.com/Debaucus/pokealarm for details.

---

# PokeAlarm Shiny Icons
Icons to be used for PokeAlarm. These icons specifically show which Pokemon are able to be Shiny via an added Watermark displaying a shiny chance upon clicking. Using original Pokemon Go assets as a base.

# What Pokemon are marked as Shiny chance?
Pokemon which can be shiny from these actions are marked as shiny chance:
- Quest Rewards
- Encounter
- Raid
- Special Research (Weekly Box)

# How to use these icons:
Inside your alarms.json in PokeAlarm use this line.

      "icon_url":"https://raw.githubusercontent.com/Debaucus/PAIcons/master/Live/pokemon_icon_<mon_id_3>_<form_id_2>.png",

Change "icon_url" for "avatar_url" or for whatever else you wish.

# Credit to:
- Image Assets with correct naming https://github.com/whitewillem/PogoAssets - Thanks Jim-Bean for linking me!
- Images created using https://overbits.herokuapp.com/watermark/ - Thanks for the awesome site!
