# 研历 2026 / Research Almanac 2026

Two static, dependency-free-at-runtime research calendars:

- [中文版](./research-calendar-2026.html): daily research 宜/忌, Mainland China 2026 holiday adjustments, selected science dates, and solemn handling of remembrance days.
- [English edition](./research-calendar-2026-en.html): the same daily almanac-based research mapping in English, with selected international science observances and no country-specific holidays.

Keep both HTML files alongside `almanac-2026.js` and `research-mapping.js`. Open either HTML file locally or serve the directory as a static website. No build step or network request is needed to view the calendars.

The original daily 宜/忌 entries were generated for all 365 days of 2026 with [lunar-javascript v1.7.7](https://github.com/6tail/lunar-javascript) (MIT; © 2018 6tail). `research-mapping.js` contains the hand-written source-term → research-action analogies; each page shows the selected terms and lets visitors expand the full daily list. To regenerate the data file, install `lunar-javascript@1.7.7` and run `node generate-almanac.cjs` in this directory.

Traditional almanac editions can disagree; these analogies are not scientific predictions or advice about actual submission timing. The Chinese edition's holiday schedule follows the [State Council's 2026 notice](https://big5.www.gov.cn/gate/big5/www.gov.cn/zhengce/zhengceku/202511/content_7047091.htm).
