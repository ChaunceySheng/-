
「韵序双拼」是一种简约的纯净的双拼输入方案，适用于「中州韵」输入法（RIME）。

包括三种配方：

第一种「韵序双拼」yunxu.schema.yaml 最为轻便，只需单独下载本文件添加到「中州韵」用户文件夹中，部署后即可使用，无需下载其他文件。
    该方案直接调用「中州韵」系统内置的「朙月拼音」词典。
    
第二种「韵序双拼解字」yunxu_radical.schema.yaml 功能更全，具有拆字输入、偏旁检字（类似音形辅码）功能， 以及 Emoji 输入功能。
    除下载本配方文件外，还需下载 lua 文件夹、 radical_pinyin.dict.yaml、radical_pinyin.schema.yaml，用于拆字输入和偏旁检字；下载 opencc 文件夹用于输入 Emoji。
    其中 radical_pinyin.schema.yaml 为 「部件拆字」输入方案，可以单独安装，也可以不安装。其功能已集成于「韵序双拼解字」中。
    分号键为功能键。双拼输入时，输入分号键即可检字。如果输入前先按分号键，则为拆字输入模式。
    radical_pinyin.schema.yaml 本由 Mirtle 创作，支持全拼双拼输入，我又在其中额外增添了「韵序双拼」输入功能。
    
第三种「掌上韵序双拼解字」yunxu_radical_m.schema.yaml 适用于「小企鹅」输入法安卓版（Fcitx5 for Android）的「中州韵」插件。
    本方案与第二种基本相同，仅针对手机「小企鹅」键盘界面做了一些调整。将功能键由分号改为井号。
    
