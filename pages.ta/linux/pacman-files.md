# pacman --files

> ஆர்ச் லினக்ஸ் தொகுப்பு மேலாளர் பயன்பாடு.
> இதையும் பார்க்கவும்: `pacman`, `pkgfile`.
> மேலும் விவரத்திற்கு: <https://manned.org/pacman.8>.

- தொகுப்பு தரவுத்தளத்தைப் புதுப்பிக்கவும்:

`sudo pacman --files --refresh`

- ஒரு குறிப்பிட்ட கோப்பை வைத்திருக்கும் தொகுப்பைக் கண்டறியவும்:

`pacman --files {{கோப்பு_பெயர்}}`

- வழக்கமான வெளிப்பாட்டைப் பயன்படுத்தி, ஒரு குறிப்பிட்ட கோப்பை வைத்திருக்கும் தொகுப்பைக் கண்டறியவும்:

`pacman --files --regex '{{வழக்கமான_வெளிப்பாடு}}'`

- தொகுப்பு பெயர்களை மட்டும் பட்டியலிடுங்கள்:

`pacman --files --quiet {{கோப்பு_பெயர்}}`

- குறிப்பிட்ட தொகுப்புக்கு சொந்தமான கோப்புகளை பட்டியலிடுங்கள்:

`pacman --files --list {{நிரல்தொகுப்பு}}`

- உதவியைக் காட்டு:

`pacman --files --help`
