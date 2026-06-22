# 发布说明 / Release Notes / Options Level Pro 1.0.0 / ATAS 8.x

这是适用于 ATAS 8.x 的 Options Level Pro 正式发布包。

This is a stable Options Level Pro release package for ATAS 8.x.

## 修复 / Fixed

- 合并本地历史缓存为 `options_level_pro_history.json`，按品种保存历史关键位。
  Merged local history cache into `options_level_pro_history.json`, grouped by symbol.
- 兼容旧的 `options_level_pro_history_{symbol}.json` 文件并在加载时迁移。
  Compatible with legacy `options_level_pro_history_{symbol}.json` files and migrates them while loading.
- 修复历史 VolTrig、Combo、Large Gamma 等关键位的类型恢复、颜色和显示。
  Fixed historical VolTrig, Combo, Large Gamma, and related level type restore, color, and visibility.

## 提醒 / Note

请下载与你 ATAS 大版本一致的 DLL，不要混用不同 ATAS 大版本的 DLL。

Download the DLL that matches your ATAS major version. Do not mix DLLs across ATAS versions.