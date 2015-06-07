This is a distribution of files which are necessary in order to run
[Antares][antares], but which are licensed separately from the
application.  They are derivative works of the "Ares Media" release,
which prohibits commercial use.  Because of the license differences, and
because these files change much more rarely than the Antares source,
they are in a separate repository.

Contents:

- fonts/

  Original data: 'nlFM' and 'nlFD' resources from "Ares Interfaces".
  Five fonts have been included: 'nlFM' ID 5000 (tactical), 5001
  (computer), 5002 (button), 5004 (title), and 5005 (button-small), and
  the corresponding 'nlFD' resources.  Initial conversion was done with
  Antares's [scripts/build-font][build-font].

- interfaces/

  Original data: 'intr' resources from "Ares Interfaces".  Some unused
  resources were excluded; in addition, interfaces corresponding to
  multiplayer were excluded.  Initial conversion was done with Antares's
  [scripts/build-interface][build-interface].  Subsequent to that, the
  key options screen was consolidated by hand.

- music/

  Original data: 'MADH' resources from "Ares Sounds".  Conversion to S3M
  was done with [PlayerPro][playerpro].

- pictures/

  Original data: 'PICT' resources from "Ares Interfaces", as well as
  'PICT' 502 (the splash screen) from the application bundle and 'PICT'
  2005 (the default scroll text background) and 8000 (the starmap) from
  "Ares Scenarios".  Some obsolete images were excluded, as well as
  anything with the Ambrosia logo.  Conversion was done with rezin.

- rotation-table

  Original data: 'rot ' resource 500 from the application.  No
  conversion was done.

- strings/

  Original data: 'STR#' resources from the application and "Ares
  Interfaces".  Conversion was done with [rezin][rezin].

- text/

  Original data: 'TEXT' resources from the application and "Ares
  Interfaces".  Conversion was done with rezin.  The credits text
  (6500.txt) was modified to add a disclaimer required by the terms of
  the CC-BY-NC-SA license.

Older, now-unneeded resources are kept in the "attic" branch.

[antares]:          https://github.com/arescentral/antares
[build-font]:       https://github.com/arescentral/antares/blob/develop/scripts/build-font
[build-interface]:  https://github.com/arescentral/antares/blob/develop/scripts/build-interface
[playerpro]:        http://playerpro.sourceforge.net/
[rezin]:            https://github.com/sfiera/rezin
