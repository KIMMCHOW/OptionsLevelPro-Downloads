# Release Notes / Options Level Pro 1.0.0 / ATAS 7.x

杩欐槸閫傜敤浜?ATAS 7.x 鐨?Options Level Pro 绋冲畾鐗堝彂甯冨寘銆?This is a stable Options Level Pro release package for ATAS 7.x.

## Contents / 鍐呭

- 閲嶆柊寤虹珛 1.0.0 鍘嗗彶缂撳瓨閫昏緫锛氱粺涓€浣跨敤 `options_level_pro_history.json` 鍏ㄩ噺鏂囦欢锛屼笉鍐嶄笅杞芥垨渚濊禆 `options_level_pro_history_NQ.json`銆?- Rebuilt 1.0.0 history-cache logic: use the full-data `options_level_pro_history.json` file instead of downloading or depending on `options_level_pro_history_NQ.json`.
- 鍐欏洖鍘嗗彶缂撳瓨鏃跺彧鏇存柊褰撳墠鍝佺鐨?`symbols.{symbol}.history`锛屼繚鐣欏悓涓€鏂囦欢鍐呭叾瀹冨搧绉嶆暟鎹€?- History writes update only `symbols.{symbol}.history` for the current symbol and preserve other symbols in the same file.
- 淇濈暀 Options key-level horizontal line rendering銆丟C / MGC key-level drawing behavior銆丟C / MGC OI label display銆?- Keeps options key-level horizontal line rendering, GC / MGC key-level drawing behavior, and GC / MGC OI label display.
- 鍗曠嫭鎻愪緵 ATAS 7.x DLL archive銆?- Separate ATAS 7.x DLL archive.

## Note / 娉ㄦ剰

璇蜂笅杞戒笌 ATAS 鐗堟湰鍖归厤鐨?DLL锛屼笉瑕佹贩鐢ㄤ笉鍚?ATAS 鐗堟湰鐨?DLL銆?Download the DLL that matches your ATAS version. Do not mix DLLs across ATAS versions.
