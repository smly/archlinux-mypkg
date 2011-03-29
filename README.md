# archlinux-mypkg

PKGBUILDs and patches

## howm

- 1.3.8 to 1.3.9.1

## nicovideo-dl

- overwrite_option patch
 - 上書き保存したくないのでオプション追加

## smlnj

- 110.71-1 to 110.72-1 (out-of-date)

## bin32-acroread-ja

- japanese font
 - 日本語フォントが足りないと怒られるので古いバージョンから取り出す

## w3m

- 0.5.2 (out-of-date)
 - nicovideo.jp cookie patch
 - nicovideo.jp の変な cookie 対策 (注: 他, accept_media に application/* を追加する必要がある)
 - ref: http://ya.maya.st/d/200607a.html#s20060704_2 
- mouseless browsing patch
 - ref: http://assam-at-night.blogspot.com/2007/05/w3mpatch-2.html
 - 上のパッチを 0.5.2 に対応

