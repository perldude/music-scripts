# music-scripts

Some scripts I use in MacOS Music/iTunes that help me manage adding new music.

## Capitalize Titles

Sometimes you import music and the capitalization is all over the place. With this you select songs, run it, and the first letter of each word is capitalized. It even knows to capitalize `(foo)` as `(Foo)`.

## Change Play Count

I didn't write this but it did inspire me to write the other scripts. You can find it [here](https://github.com/davidjb/itunes-change-play-count).

## Number Tracks

Oftentimes, tracks come with the track numbers at the beginning of the title string but not in the track field. This takes a list of selected tracks and put the track number in the track field, starting with the first selected track at #1. Useful for breaking up a long list of tracks into different CDs (if you're anal about things like that).

## Strip Track Numbers

Sometimes you import music and the track numbers are in the title of the song. This strips those number from the beginning of the selected tracks.

## Shift Play Count

SYIM and there's a weird thing where the leadout track is shown as track zero (or even just omitted), you select it and the rest of the tracks, and all the songs are imported (except the first track) but the titles are shifted up by one. The last track is left with a file name for a track. This asks you for the name of the first track, puts that in its name, then shifts the rest of the songs down by one.
