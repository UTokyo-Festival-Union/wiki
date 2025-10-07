# wiki
本レポジトリは、駒場祭委員会、五月祭常任委員会及び東京大学教養学部オリエンテーション委員会の共同プログラム開発に関する協定（以下単に「協定」といいます。）及び、駒場祭委員会、五月祭常任委員会及び東京大学教養学部オリエンテーション委員会の共同プログラム開発に関する協定の実施に伴う駒場祭委員会及び五月祭常任委員会による共同プログラム開発に関する覚書（以下単に「覚書」といいます。）の規定に基づき、協定（各会において公示されます。）と覚書、その他の開発ルールについて公開するものです。

## フォルダ構造
「agreement」には協定を保管します。 agreement.md が現在施行中の本文です。 amendment フォルダ以下には、協定を改正する協定を含め、関連協定の成立年月日のフォルダがあります（なお、「_enactment」は制定当初を示します。）。 meta.md には諸情報が、 text.md には本文が、original.pdf には原本が、また、 comparative_table.pdf には改正する協定に関する新旧対照表が保管されています。

「mou」には覚書を保管します。内部の構造については、上記に準じます。

「rules」には覚書に記載しない程度の仔細の開発ルールを保管しています。

<pre>
├── agreement
│   ├── agreement.md
│   └── amendment
│       └── 20241222_enactment
│           ├── meta.md
│           ├── original.pdf
│           └── text.md
├── mou
│   ├── amendment
│   │   ├── 20241223_enactment
│   │   │   ├── meta.md
│   │   │   ├── original.pdf
│   │   │   └── text.md
│   │   └── 20xxxxxx
│   │   │   ├── comparative_table.pdf
│   │   │   ├── meta.md
│   │   │   ├── original.pdf
│   │   │   └── text.md
│   │   ...
│   └── mou.md
├── README.md
└── rules
    │ 
    ...
</pre>
