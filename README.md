# 『現代日本語書き言葉均衡コーパス』新聞記事データ記事分類別短単位語彙表（分類語彙表番号つき）(BCCWJ-PNmeta-WSD-frequency version 2024.10)

## Description

『現代日本語書き言葉均衡コーパス』(BCCWJ)に分類語彙表番号を自動付与した BCCWJ-WSD の頻度表
新聞記事データ (PN) に対して、新聞記事の記事分類(BCCWJ-PNmeta)を付与し、記事分類ごとに集計したもの

## Features

- bccwj_pnmeta_suw_wsd_freq.txt 新聞記事データ(PN) 語彙頻度表
- bccwj_pnmeta_suw_wsd_freq.xlsx 新聞記事データ(PN) 語彙頻度表 （上記テキストデータと同じものです）


## Format

1行目がヘッダ行

1. BCCWJ-PNmeta:新聞名
2. BCCWJ-PNmeta:掲載紙面
3. BCCWJ-PNmeta:記事種別A
4. BCCWJ-PNmeta:記事種別
5. BCCWJ-PNmeta:内外
6. BCCWJ-PNmeta:分類（大）
7. BCCWJ-PNmeta:分類（小）
8. BCCWJ-meta:朝夕
9. BCCWJ-meta:出版年
10. UniDic:lForm 語彙素読み(UniDic)
11. UniDic:lemma 語彙素(UniDic)
12. UniDic:pos 品詞(UniDic)
13. UniDic:subLemma 語彙素細分類(UniDic)
14. UniDic:wType 語種(UniDic)
15. WLSP:article number 分類番号(分類語彙表)
16. WLSP:class 類(分類語彙表)
17. WLSP:division 部門(分類語彙表)
18. WLSP:section 中項目(分類語彙表)
19. WLSP:article 分類項目(分類語彙表)
20. frequency 頻度
21. pmw 100万語あたりの調整頻度

## Creators

- 浅田 宗磨(東京農工大学)
- 古宮 嘉那子(東京農工大学)

## References

- 浅田 宗磨・古宮 嘉那子・浅原 正幸 (2024) 「『現代日本語書き言葉均衡コーパス』に対する分類語彙表番号悉皆付与」言語処理学会第30回年次大会(NLP2024)
- 加藤 祥・浅原 正幸 (2023) 「『現代日本語書き言葉均衡コーパス』新聞サブコーパスの記事情報」 日本語の研究 19巻2豪 p.206-214.
  - https://github.com/masayu-a/BCCWJ-PNmeta

## License

ラベル部分は CC BY-NC-ND 4.0 
（本文の復元性が高いために、有償契約者のみに「中納言」ダウンロードサーバにて配布）

## Credit

国立国語研究所 (2024) 『現代日本語書き言葉均衡コーパス』短単位語彙表（分類語彙表番号つき）(BCCWJ-PNmeta-WSD-frequency version 2024.03)

本データは、科研費 22K12145, 18K00634 および国立国語研究所共同研究プロジェクト「アノテーションデータを用いた実証的計算心理言語学」によるものです。

## Contact

kotonoha@ninjal.ac.jp

## History

- (BCCWJ-WSD-PNmeta-frequency version 2024.03) から (BCCWJ-WSD-PNmeta-frequency version 2024.10) への変更点

subLemma の列を変更
