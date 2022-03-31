# HwPrc Cubase Drum Maps (2022-03-31)

Cubase Drum Maps (`.drm` preset files) for **East West Hollywood Orchestral
Percussion** (Opus Edition Diamond), including **Hollywood Harp**.

Put together by [Eric Barndollar](https://barndollarmusic.com). Feel free to use
and share!

These were generated from
[this CSV spreadsheet](HwPrcDrumMaps.csv) using the
[`mapdrums`](https://github.com/barndollarmusic/mapdrums) command-line script.
If you would like to customize, you can edit that `.csv` file using a
spreadsheet program like Google Sheets or Excel and then use the `mapdrums`
script to re-generate the `.drm` preset files.


## How to Use in Your Cubase Projects

1. Put these `.drm` files anywhere you want. I like to make a custom subfolder
   called `Drum Map Presets` within my Cubase template project for the library.

2. In Cubase, with a MIDI or Instrument Track selected, open the Inspector (the
   left zone on the side of the track list) top section and click the `Drum
   Maps` menu > `Drum Map Setup...`

3. In the Drum Map Setup dialog, use the top-left `Functions` menu > `Load...`
   and select all of the `.drm` files you want to import into the project (you
   can select them all at once). Close the Drum Map Setup dialog.

4. For each MIDI or Instrument Track, select the appropriate drum map preset for
   that instrument under the `Drum Maps` menu in the top-left Inspector
   section's `Drum Maps` menu.

5. When editing MIDI on tracks when you have a Drum Map configured, Cubase will
   default to using the **Drum Editor** (<u>tip</u>: toggle the *Show Note
   Length* button on in the Notes Length section of the toolbar). Or you can
   change this default in Cubase Preferences, under `Editors` > `Use Drum Editor
   when Drum Map is assigned`. The **Key Editor** will show the sound label on
   notes if you are zoomed in enough, but it doesn't show you all of the
   available sound labels like the Drum Editor does.


## Version Information

Made with these sample library and player versions:

- Hollywood Orchestral Percussion (Opus Edition Diamond)<br>
  (ewu/ewus `1.0.1`; ewui `1.0.7`; latest version as of March 2022)
- Opus Player `1.1.0` (2021-10-19)

*Future library updates could potentially change these mappings.*


## Notes

### General
- Labels `[1]`, `[2]`, *etc.* usually go from lowest pitched to highest pitched.

### Snare Drums, Field Drums
- `55` Roll Cresc: only available for some of the drums.

### Tam-Tam
- Bowed SFX, Scraped SFX only available for 38" Large Tam-Tam.

### Brake Drum, Anvils, Metal Rails
- Hard to tell which instruments are which, so I left `(?)` in labels.

### Mark Tree
- `67` Sus Mid: only available for Double Length Mark Tree.

### Shakers
- Library actually provides 7 Shakers, but the lowest 4 are so noisy that I
  pretend that only the top 3 are available.

### Harp
Glissando scale descriptions in the East West manual are very far off base, so I
did my best to quickly transcribe the actual scales played.

Here are pedals for some of the more complex ones:

- **~Fdim7 Synthetic**: D# Cb B# | E# Fb G# Ab
- **Dbmaj7#11 Pentatonic**: Db C# B# | E# F G Ab
- **~F#dim7 Synthetic**: Db C B# | Eb F Gb A


## For More Virtual Orchestra Template Resources

Hope these drum maps are useful for you. I plan to share a lot more presets and
resources like these soon here:
[barndollarmusic.com/vorch](https://barndollarmusic.com/vorch)
