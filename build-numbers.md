# 代码名称，标签和版本号

概括来说，Android 的开发发生在各发布集合中，它使用可口美食作为代码名称，并按字母顺序排列。

## 平台代码名称，版本，API 等级和 NDK 发布

代码名称与下面的版本号匹配，下表也提供了相应的 API 级别和 NDK 版本方便查询：

| 代码名称 | 版本 | API等级 |
| --- | --- | --- |
| Lollipop | 5.1 | API level 22 |
| Lollipop | 5.0 | API level 21 |
| KitKat | 4.4 - 4.4.4 | API level 19 |
| Jelly Bean | 4.3.x | API level 18 |
| Jelly Bean | 4.2.x | API level 17 |
| Jelly Bean | 4.1.x | API level 16 |
| Ice Cream Sandwich | 4.0.3 - 4.0.4 | API level 15, NDK 8 |
| Ice Cream Sandwich | 4.0.1 - 4.0.2 | API level 14, NDK 7 |
| Honeycomb | 3.2.x | API level 13 |
| Honeycomb | 3.1 | API level 12, NDK 6 |
| Honeycomb | 3.0 | API level 11 |
| Gingerbread | 2.3.3 - 2.3.7 | API level 10 |
| Gingerbread | 2.3 - 2.3.2 | API level 9, NDK 5 |
| Froyo | 2.2.x | API level 8, NDK 4 |
| Eclair | 2.1 | API level 7, NDK 3 |
| Eclair | 2.0.1 | API level 6 |
| Eclair | 2.0 | API level 5 |
| Donut | 1.6 | API level 4, NDK 2 |
| Cupcake | 1.5 | API level 3, NDK 1 |
| (no code name) | 1.1 | API level 2 |
| (no code name) | 1.0 | API level 1 |

从蛋糕开始，各独立版本由一个短的版本代码来区分，如 FRF85B。

第一个字母代表的是版本集合的名称，例如 F 就是 Froyo。

第二个字母就是让谷歌识别确切的代码分支是从哪里来。按照约定，R 代表的是主发布分支。

下一个字母和两个数字是一个日期代码。字母是计算季度的，A 代表 2009 年第一季度。因此，F 代表 2010 年第二季度。两个数字代表在这个季度中的天数。F85 代表的是 2010 年 6 月 24 日。

最后，最后的字母标识与同一日期代码各个版本，依次以 A 开头的；A 实际上隐含的，通常省略。

日期代码不能保证版本的确切的日期，通常它将微小变化加入到现有的版本中，在现有版本中重复使用相同的日期代码。

## 源代码标签和版本

从甜甜圈开始，准确的标签列表和版本显示在下表中。用于 Nexus 设备的出厂镜像和二进制文件可以从以下网址下载：

[](https://developers.google.com/android/nexus/images)[https://developers.google.com/android/nexus/images](https://developers.google.com/android/nexus/images)

[](https://developers.google.com/android/nexus/drivers)[https://developers.google.com/android/nexus/drivers](https://developers.google.com/android/nexus/drivers)

| 内部版本 | 分支 | 外部版本 | 支持设备 |
| --- | --- | --- | --- |
| LMY47Z | android-5.1.1_r4 | Lollipop | Nexus 6 (For Sprint, USC ONLY) |
| LMY48B | android-5.1.1_r3 | Lollipop | Nexus 5 |
| LMY47X | android-5.1.1_r2 | Lollipop | Nexus 9 (volantis) |
| LMY47V | android-5.1.1_r1 | Lollipop | Nexus 7 (flo/grouper), Nexus 10, Nexus Player |
| LMY47O | android-5.1.0_r5 | Lollipop | Nexus 4, Nexus 7 (flo/deb) |
| LMY47M | android-5.1.0_r4 | Lollipop | Nexus 6 (For T-Mobile ONLY) |
| LMY47I | android-5.1.0_r3 | Lollipop | Nexus 5, Nexus 6 |
| LMY47E | android-5.1.0_r2 | Lollipop | Nexus 6 |
| LMY47D | android-5.1.0_r1 | Lollipop | Nexus 5, Nexus 6, Nexus 7 (grouper/tilapia), Nexus 10, Nexus Player |
| LRX22L | android-5.0.2_r3 | Lollipop | Nexus 9 (volantis/volantisg) |
| LRX22G | android-5.0.2_r1 | Lollipop | Nexus 7 (flo/deb/grouper/tilapia), Nexus 10 |
| LRX22C | android-5.0.1_r1 | Lollipop | Nexus 4, Nexus 5, Nexus 6 (shamu), Nexus 7 (flo), Nexus 9 (volantis/volantisg), Nexus 10 |
| LRX21V | android-5.0.0_r7.0.1 | Lollipop | Nexus Player (fugu) |
| LRX21T | android-5.0.0_r6.0.1 | Lollipop | Nexus 4 |
| LRX21R | android-5.0.0_r5.1.0.1 | Lollipop | Nexus 9 (volantis) |
| LRX21Q | android-5.0.0_r5.0.1 | Lollipop | Nexus 9 (volantis) |
| LRX21P | android-5.0.0_r4.0.1 | Lollipop | Nexus 7 (flo/grouper), Nexus 10 |
| LRX21O | android-5.0.0_r3.0.1 | Lollipop | Nexus 5 (hammerhead), Nexus 6 (shamu) |
| LRX21M | android-5.0.0_r2.0.1 | Lollipop | Nexus Player (fugu) |
| LRX21L | android-5.0.0_r1.0.1 | Lollipop | Nexus 9 (volantis) |
| KTU84Q | android-4.4.4_r2 | KitKat | Nexus 5 (hammerhead) (For 2Degrees/NZ, Telstra/AUS and India ONLY) |
| KTU84P | android-4.4.4_r1 | KitKat | Nexus 5, Nexus 7 (flo/deb/grouper/tilapia), Nexus 4, Nexus 10 |
| KTU84M | android-4.4.3_r1.1 | KitKat | Nexus 5 (hammerhead) |
| KTU84L | android-4.4.3_r1 | KitKat | Nexus 7 (flo/deb/grouper/tilapia), Nexus 4, Nexus 10 |
| KVT49L | android-4.4.2_r2 | KitKat | Nexus 7 (deb Verizon) |
| KOT49H | android-4.4.2_r1 | KitKat | Nexus 5, Nexus 7 (flo/deb/grouper/tilapia), Nexus 4, Nexus 10 |
| KOT49E | android-4.4.1_r1 | KitKat | Nexus 5, Nexus 7 (flo/deb/grouper/tilapia), Nexus 4, Nexus 10 |
| KRT16S | android-4.4_r1.2 | KitKat | Nexus 7 (flo/deb/grouper/tilapia), Nexus 4, Nexus 10 |
| KRT16M | android-4.4_r1 | KitKat | Nexus 5 (hammerhead) |
| JLS36I | android-4.3.1_r1 | Jelly Bean | Nexus 7 (deb) |
| JLS36C | android-4.3_r3 | Jelly Bean | Nexus 7 (deb) |
| JSS15R | android-4.3_r2.3 | Jelly Bean | Nexus 7 (flo) |
| JSS15Q | android-4.3_r2.2 | Jelly Bean | Nexus 7 (flo) |
| JSS15J | android-4.3_r2.1 | Jelly Bean | Nexus 7 (flo/deb) |
| JSR78D | android-4.3_r2 | Jelly Bean | Nexus 7 (deb) |
| JWR66Y | android-4.3_r1.1 | Jelly Bean | Galaxy Nexus, Nexus 7 (grouper/tilapia), Nexus 4, Nexus 10 |
| JWR66V | android-4.3_r1 | Jelly Bean | Galaxy Nexus, Nexus 7 (grouper/tilapia), Nexus 4, Nexus 10 |
| JWR66N | android-4.3_r0.9.1 | Jelly Bean | Galaxy Nexus, Nexus 7 (grouper/tilapia/flo), Nexus 4, Nexus 10 |
| JWR66L | android-4.3_r0.9 | Jelly Bean | Nexus 7 |
| JDQ39E | android-4.2.2_r1.2 | Jelly Bean | Nexus 4 |
| JDQ39B | android-4.2.2_r1.1 | Jelly Bean | Nexus 7 |
| JDQ39 | android-4.2.2_r1 | Jelly Bean | Galaxy Nexus, Nexus 7, Nexus 4, Nexus 10 |
| JOP40G | android-4.2.1_r1.2 | Jelly Bean | Nexus 4 |
| JOP40F | android-4.2.1_r1.1 | Jelly Bean | Nexus 10 |
| JOP40D | android-4.2.1_r1 | Jelly Bean | Galaxy Nexus, Nexus 7, Nexus 4, Nexus 10 |
| JOP40C | android-4.2_r1 | Jelly Bean | Galaxy Nexus, Nexus 7, Nexus 4, Nexus 10 |
| JZO54M | android-4.1.2_r2.1 | Jelly Bean |
| JZO54L | android-4.1.2_r2 | Jelly Bean |
| JZO54K | android-4.1.2_r1 | Jelly Bean | Nexus S, Galaxy Nexus, Nexus 7 |
| JRO03S | android-4.1.1_r6.1 | Jelly Bean | Nexus 7 |
| JRO03R | android-4.1.1_r6 | Jelly Bean | Nexus S 4G |
| JRO03O | android-4.1.1_r5 | Jelly Bean | Galaxy Nexus |
| JRO03L | android-4.1.1_r4 | Jelly Bean | Nexus S |
| JRO03H | android-4.1.1_r3 | Jelly Bean |
| JRO03E | android-4.1.1_r2 | Jelly Bean | Nexus S |
| JRO03D | android-4.1.1_r1.1 | Jelly Bean | Nexus 7 |
| JRO03C | android-4.1.1_r1 | Jelly Bean | Galaxy Nexus |
| IMM76L | android-4.0.4_r2.1 | Ice Cream Sandwich |
| IMM76K | android-4.0.4_r2 | Ice Cream Sandwich | Galaxy Nexus |
| IMM76I | android-4.0.4_r1.2 | Ice Cream Sandwich | Galaxy Nexus |
| IMM76D | android-4.0.4_r1.1 | Ice Cream Sandwich | Nexus S, Nexus S 4G, Galaxy Nexus |
| IMM76 | android-4.0.4_r1 | Ice Cream Sandwich |
| IML77 | android-4.0.3_r1.1 | Ice Cream Sandwich |
| IML74K | android-4.0.3_r1 | Ice Cream Sandwich | Nexus S |
| ICL53F | android-4.0.2_r1 | Ice Cream Sandwich | Galaxy Nexus |
| ITL41F | android-4.0.1_r1.2 | Ice Cream Sandwich | Galaxy Nexus |
| ITL41D | android-4.0.1_r1.1 | Ice Cream Sandwich | Galaxy Nexus |
| ITL41D | android-4.0.1_r1 | Ice Cream Sandwich | Galaxy Nexus |
| GWK74 | android-2.3.7_r1 | Gingerbread | Nexus S 4G |
| GRK39F | android-2.3.6_r1 | Gingerbread | Nexus One, Nexus S |
| GRK39C | android-2.3.6_r0.9 | Gingerbread | Nexus S |
| GRJ90 | android-2.3.5_r1 | Gingerbread | Nexus S 4G |
| GRJ22 | android-2.3.4_r1 | Gingerbread | Nexus One, Nexus S, Nexus S 4G |
| GRJ06D | android-2.3.4_r0.9 | Gingerbread | Nexus S 4G |
| GRI54 | android-2.3.3_r1.1 | Gingerbread | Nexus S |
| GRI40 | android-2.3.3_r1 | Gingerbread | Nexus One, Nexus S |
| GRH78C | android-2.3.2_r1 | Gingerbread | Nexus S |
| GRH78 | android-2.3.1_r1 | Gingerbread | Nexus S |
| GRH55 | android-2.3_r1 | Gingerbread | earliest Gingerbread version, Nexus S |
| FRK76C | android-2.2.3_r2 | Froyo |
| FRK76 | android-2.2.3_r1 | Froyo |
| FRG83G | android-2.2.2_r1 | Froyo | Nexus One |
| FRG83D | android-2.2.1_r2 | Froyo | Nexus One |
| FRG83 | android-2.2.1_r1 | Froyo | Nexus One |
| FRG22D | android-2.2_r1.3 | Froyo |
| FRG01B | android-2.2_r1.2 | Froyo |
| FRF91 | android-2.2_r1.1 | Froyo | Nexus One |
| FRF85B | android-2.2_r1 | Froyo | Nexus One |
| EPF21B | android-2.1_r2.1p2 | Eclair |
| ESE81 | android-2.1_r2.1s | Eclair |
| EPE54B | android-2.1_r2.1p | Eclair | Nexus One |
| ERE27 | android-2.1_r2 | Eclair | Nexus One |
| ERD79 | android-2.1_r1 | Eclair | Nexus One |
| ESD56 | android-2.0.1_r1 | Eclair |
| ESD20 | android-2.0_r1 | Eclair |
| DMD64 | android-1.6_r1.5 | Donut |
| DRD20 | android-1.6_r1.4 |
| DRD08 | android-1.6_r1.3 |
| DRC92 | android-1.6_r1.2 |

分支 froyo, gingerbread, ics-mr0, ics-mr1, jb-dev, jb-mr1-dev, jb-mr1.1-dev, jb-mr2-dev, kitkat-dev 为代表的开发分支不完全匹配配置。这是由谷歌测试提供的结果。他们可能含有除了官方标记发布之外的各种变化和那些没有彻底的测试的开发分支。

为了区别各版本，你可以得到每个项目有关的变化列表，通过发出以下命令，并向其传递两个分支标签相关的变化列表：

```
$ repo forall -pc 'git log --no-merges --oneline branch-1..branch-2'
```

例如：

```
$ repo forall -pc 'git log --no-merges --oneline android-4.4.2_r2..android-4.4.2_r1'
```

输出到文本文件中：

```
repo forall -pc 'git log --no-merges --oneline android-4.4.2_r2..android-4.4.2_r1' > /tmp/android-4.4.2_r2-android-4.4.2_r1-diff.txt
```

## 蜂窝版本的 GPL 模块

对于蜂窝，整个平台的源代码是不可用。然而，下列标签显示的是部分在 GPL 和 LGPL 许可下的蜂窝源代码：

| 内部版本 | 标签 | 备注 |
| --- | --- | --- |
| HRI39 | android-3.0_r1 | 最早的蜂窝版本 |
| HRI66 | android-3.0_r1.1 |
| HWI69 | android-3.0_r1.2 |
| HRI83 | android-3.0_r1.3 |
| HMJ37 | android-3.1_r1 |
| HTJ85B | android-3.2_r1 |
| HTK55D | android-3.2.1_r1 |
| HTK75D | android-3.2.1_r2 |
| HLK75C | android-3.2.2_r1 |
| HLK75D | android-3.2.2_r2 |
| HLK75F | android-3.2.4_r1 |
| HLK75H | android-3.2.6_r1 | 最后的蜂窝版本 |

没有证明显示上面表格中包含准确源代码。然而，有证明显示允许建立这些组件。下面的命令是为 3.0_r1.1 工作的，并且其它版本可通过切换 GIT 中 checkout 参数进行使用。如果必要的话，-m 参数需要重置。Git 的 checkout 命令会输出一个非 GPL 的项目的错误，如果不能在问题中找到标记。

```
$ repo init -b master -m base-for-3.0-gpl.xml
$ repo sync
$ repo forall -c git checkout android-3.0_r1.1
```
