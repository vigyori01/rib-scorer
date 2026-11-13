# RIB Scorer

A fast, phone-first scoring app for sailing coaches. Record finishes from the coach boat (RIB) with big tap buttons and see live standings.

## Features
- **Entry list upload:** CSV, TXT or Excel (.xlsx), or paste from a spreadsheet. Sail / Name / Club columns are detected automatically.
- **Finish recording:** tap boats in finishing order, undo, filter by sail number, hide boats that have finished. Hold a boat to move it, remove it or give it a code.
- **Start penalties:** a separate BFD / UFD / OCS / DNS / DNC screen. Boats with a penalty are taken out of the finish count automatically.
- **Live standings:** Low Point System (RRS Appendix A), entries + 1 for codes, configurable discards, A8 tie-breaks, optional live race.
- **Import earlier results:** load official results so far from a PDF (Sailwave, Manage2Sail…), Excel, CSV or pasted text. Imported races are added to the event, and new races you score continue after them. Tap any cell in Results to correct a score.
- **Copy results** as a table you can paste into Excel or Sheets.
- Data is saved in the browser on your device (localStorage). Use *Copy backup* / *Restore backup* in Setup to move it.

## Use it
It's a single `index.html` with no build step. Open it in a browser, or turn on GitHub Pages (Settings → Pages → Deploy from branch → `main` / root) and open the page on your phone. Add it to your home screen for quick access.

Excel import loads SheetJS, and PDF import loads PDF.js, from cdnjs the first time you use them.
