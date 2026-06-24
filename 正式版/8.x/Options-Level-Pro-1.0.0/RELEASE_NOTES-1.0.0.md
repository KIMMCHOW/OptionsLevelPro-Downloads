# Release Notes / Options Level Pro 1.0.0 / ATAS 8.x

This is a stable Options Level Pro 1.0.0 release package for ATAS 8.x.

## Fixed

- Fixed the occasional `0.00` horizontal line by fully hiding the default ATAS value series and filtering non-positive level prices.
- Moved the protected API default endpoint to the formal TradingHub HTTPS domain after the Singapore server migration.


## Changed

- Rebuilt the history-cache logic to use the full-data `options_level_pro_history.json` file instead of downloading or depending on `options_level_pro_history_NQ.json`.
- History writes update only `symbols.{symbol}.history` for the current symbol and preserve other symbols in the same file.
- Provides a separate ATAS 8.x DLL archive.

## Note

Download the DLL that matches your ATAS version. Do not mix DLLs across ATAS versions.
