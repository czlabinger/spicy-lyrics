# Spicy Lyrics

> [!CAUTION]
> This is still early in testing and may not work

This fork of [Spicy Lyrics](https://github.com/Spikerko/spicy-lyrics) adds the possibility to add custom servers for lyric hosting.
The list of servers is stored in `src/components/Global/Defaults.ts` under 'Defaults.lyrics.api.url'. It takes an array of servers and tries them in that order. If the lyrics are not found or the server doesn't respond correctly it tries the next one.
