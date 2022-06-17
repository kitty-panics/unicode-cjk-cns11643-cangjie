# CNS11643-Unicode-Cangjie

[CNS11643]、Unicode、Cangjie 对照表。

[CNS11643]: https://data.gov.tw/dataset/5961

## 协作整理

由于疏忽、参考资料有误等，码表可能会存在一些错误，如果你发现了错误请通过
[Issues] 或者 [PR] 反馈给我。

+ 如果不会 Git 操作可在 [Issues] 中发起反馈。
+ 如果熟悉 Git 操作可在更正错误后发起 [PR]。

[Issues]: https://github.com/kitty-panics/CNS11643-Unicode-Cangjie/issues
[PR]: https://github.com/kitty-panics/CNS11643-Unicode-Cangjie/pulls

## 数据格式

每个文件一行一字，以 Tab (制表符) 进行分割，如果某字存在多个 Cangjie 编码时，以
`,` (英文逗号) 字符进行分割，例：

```Text
U+4E00	一	1-4421	m
U+4E01	丁	1-4423	mn
U+4E0F	丏	2-212D	mlvs
U+4E18	丘	1-4563	hlm,om
```

## 文件列表

+ [All.txt] (整合下面 CJK/A/B/C/D/E/F/G/Compatibility/Compatibility-Supplement)
+ [CJK-Unified-Ideographs.txt] (中日韩统一表意文字)
    + [Basic 区没有编码的字]
+ [CJK-Unified-Ideographs-Extension-A.txt] (中日韩统一表意文字扩展区 A)
    + [A 区没有编码的字]
+ [CJK-Unified-Ideographs-Extension-B.txt] (中日韩统一表意文字扩展区 B)
    + [B 区没有编码的字]
+ [CJK-Unified-Ideographs-Extension-C.txt] (中日韩统一表意文字扩展区 C)
    + [C 区没有编码的字]
+ [CJK-Unified-Ideographs-Extension-D.txt] (中日韩统一表意文字扩展区 D)
    + [D 区没有编码的字]
+ [CJK-Unified-Ideographs-Extension-E.txt] (中日韩统一表意文字扩展区 E)
    + [E 区没有编码的字]
+ [CJK-Unified-Ideographs-Extension-F.txt] (中日韩统一表意文字扩展区 F)
    + 所有字都没有编码
+ [CJK-Unified-Ideographs-Extension-G.txt] (中日韩统一表意文字扩展区 G)
    + 所有字都没有编码
+ [CJK-Compatibility-Ideographs.txt] (中日韩兼容表意文字)
    + [Compat 区没有编码的字]
+ [CJK-Compatibility-Ideographs-Supplement.txt] (中日韩兼容表意文字增补)
    + [Compat-Supplement 区没有编码的字]

**注：**

为方便管理，将争议字符 "〇 U+3007" 由 "CJK Symbols and Punctuation (中日韩符号和标点)"
移动到 "CJK Unified Ideographs (中日韩统一表意文字)"，并置于文件开头。

[All.txt]: All.txt
[CJK-Unified-Ideographs.txt]: CJK-Unified-Ideographs.txt
[CJK-Unified-Ideographs-Extension-A.txt]: CJK-Unified-Ideographs-Extension-A.txt
[CJK-Unified-Ideographs-Extension-B.txt]: CJK-Unified-Ideographs-Extension-B.txt
[CJK-Unified-Ideographs-Extension-C.txt]: CJK-Unified-Ideographs-Extension-C.txt
[CJK-Unified-Ideographs-Extension-D.txt]: CJK-Unified-Ideographs-Extension-D.txt
[CJK-Unified-Ideographs-Extension-E.txt]: CJK-Unified-Ideographs-Extension-E.txt
[CJK-Unified-Ideographs-Extension-F.txt]: CJK-Unified-Ideographs-Extension-F.txt
[CJK-Unified-Ideographs-Extension-G.txt]: CJK-Unified-Ideographs-Extension-G.txt
[CJK-Compatibility-Ideographs.txt]: CJK-Compatibility-Ideographs.txt
[CJK-Compatibility-Ideographs-Supplement.txt]: CJK-Compatibility-Ideographs-Supplement.txt

[Basic 区没有编码的字]: 无CNS.CJK-Unified-Ideographs.txt
[A 区没有编码的字]: 无CNS.CJK-Unified-Ideographs-Extension-A.txt
[B 区没有编码的字]: 无CNS.CJK-Unified-Ideographs-Extension-B.txt
[C 区没有编码的字]: 无CNS.CJK-Unified-Ideographs-Extension-C.txt
[D 区没有编码的字]: 无CNS.CJK-Unified-Ideographs-Extension-D.txt
[E 区没有编码的字]: 无CNS.CJK-Unified-Ideographs-Extension-E.txt
[Compat 区没有编码的字]: 无CNS.CJK-Compatibility-Ideographs.txt
[Compat-Supplement 区没有编码的字]: 无CNS.CJK-Compatibility-Ideographs-Supplement.txt

## 参考资料

参考资料可在 [参考资料] 目录下找到。其中非文件类的在线资料将转换成 PDF 快照存放。

+ 2022-06-15 更新的 [CNS11643 中文標準交換碼全字庫]

[参考资料]: 参考资料
[CNS11643 中文標準交換碼全字庫]: https://data.gov.tw/dataset/5961

## 相关项目

### [cn-tables]

整理中国大陆简中、中国台湾繁中的国标汉字表。

[cn-tables]: https://github.com/kitty-panics/cn-tables

### [CNS11643-Unicode-Cangjie]

[CNS11643]、Unicode、Cangjie 对照表。

[CNS11643-Unicode-Cangjie]: https://github.com/kitty-panics/CNS11643-Unicode-Cangjie
[CNS11643]: https://data.gov.tw/dataset/5961

### [unicode-cjk]

整理所有 [Unicode] CJK 字符。

[unicode-cjk]: https://github.com/kitty-panics/unicode-cjk
[Unicode]: https://www.unicode.org/Public/UNIDATA/Blocks.txt

### [unicode-cjk-98wubi]

整理 Unicode CJK 字符的 [五笔98] 编码。

[unicode-cjk-98wubi]: https://github.com/kitty-panics/unicode-cjk-98wubi
[五笔98]: http://98wb.ysepan.com

### [unicode-cjk-ids]

备份、修补 [chise/ids]。

[unicode-cjk-ids]: https://github.com/kitty-panics/unicode-cjk-ids
[chise/ids]: http://git.chise.org/git/chise/ids.git

### [unicode-cjk-zhlf]

整理 Unicode CJK 字符的 [字海两分] 编码。

[unicode-cjk-zhlf]: https://github.com/kitty-panics/unicode-cjk-zhlf
[字海两分]: http://cheonhyeong.com/Simplified/download.html

### [unicode-cjk-zhlf-sc]

整理 Unicode CJK 字符的 [字海两分速成] 编码。

[unicode-cjk-zhlf-sc]: https://github.com/kitty-panics/unicode-cjk-zhlf-sc
[字海两分速成]: http://cheonhyeong.com/Simplified/download.html
