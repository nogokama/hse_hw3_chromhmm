# hse_hw3_chromhmm

[Колаб](https://colab.research.google.com/drive/1yjLMoZ0NAzpZZHE7AUo8lsvfw1ebA-jN#scrollTo=A3EZXj29VkoC)

## Cellmarkfiletable
![Image](/data/cellmarkfiletable.png)

## Гистоновые Метки
Histone modification | Bam file
--- | ---
H2AFZ | [wgEncodeBroadHistoneHelas3H2azAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHelas3H2azAlnRep1.bam)
H3K27ac | [wgEncodeBroadHistoneHelas3H3k27acStdAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHelas3H3k27acStdAlnRep1.bam)
H3k9ac | [wgEncodeBroadHistoneHelas3H3k9acStdAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHelas3H3k9acStdAlnRep1.bam)
H3k9me3 | [wgEncodeBroadHistoneHelas3H3k09me3AlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHelas3H3k09me3AlnRep1.bam)
H3k27me3 | [wgEncodeBroadHistoneHelas3H3k27me3StdAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHelas3H3k27me3StdAlnRep1.bam)
H3k36me3 | [wgEncodeBroadHistoneHelas3H3k36me3StdAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHelas3H3k36me3StdAlnRep1.bam)
H3k4me1 | [wgEncodeBroadHistoneHelas3H3k04me1StdAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHelas3H3k04me1StdAlnRep1.bam)
H3k4me2 | [wgEncodeBroadHistoneHelas3H3k4me2StdAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHelas3H3k4me2StdAlnRep1.bam)
H3k4me3 | [wgEncodeBroadHistoneHelas3H3k4me3StdAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHelas3H3k4me3StdAlnRep1.bam)
H3k79me2 | [wgEncodeBroadHistoneHelas3H3k79me2StdAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHelas3H3k79me2StdAlnRep1.bam)


Контрольный файл: [wgEncodeBroadHistoneHelas3ControlStdAlnRep1.bam](http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHelas3ControlStdAlnRep1.bam)

## ChromHMM

![Image](/data/16_1.png)

![17](/data/17.png)

![Image](/data/18.png) 

![Image](/data/19.png)

![Image](/data/20.png)

## Эпигенетически типы

| № | Название | Описание, метки | Картинка |
| --- | --- | --- | --- |
| 1 | Active Promoter | H4K4me3, H3K9ac, H3K27ac | ![Image](/data/1.png) |
| 2 | Weak enhancer/Weak transcribed | H3K27ac, H3K9ac, H3K4m3, H3K4m2 | ![Image](/data/2.png) |
| 3 | Strong enhancer/Transcriptional elogation | H2AFZ, H3K4me1, H3K4me2, H3K4me3, H3K9ac, H3K27ac | ![Image](/data/3.png) |
| 4 | Active Promoter | H2AFZ, H3K4me1, H3K4me2, H3K9ac, H3K27ac | ![Image](/data/4.png) |
| 5 | Active Promoter | H3K27ac, H3K4me1, H2AFZ | ![Image](/data/5.png) |
| 6 | Weak enhancer | H3K4me1, H3K4me2, H3K27ac | ![Image](/data/6.png) |
| 7 | Weak enhancer | H3K27ac, H3K9ac, H3K4me3, H3K4me2 | ![Image](/data/7.png) |
| 8 | Weak enhancer | H3K4me1, H3K4me2, H3K4me3, H3K9ac | ![Image](/data/8.png) |
| 9 | Weak enhancer | H3K4me2, H3K4me3, H3K9ac | ![Image](/data/9.png) |
| 10 | Weak transcribed | H3K79me2 | ![Image](/data/10.png) |
| 11 | Weak transcribed | H3K79me2 | ![Image](/data/11.png) |
| 12 | Weak transcribed | H3K36me3 | ![Image](/data/12.png) |
| 13 | Repressed | H3K27me3 | ![Image](/data/13.png) |
| 14 | Heterochromatin | Везде | ![Image](/data/14.png) |
| 15 | Heterochromatin | H3K4m1, H3K4m2, H3K9ac | ![Image](/data/15.png) |

Бонус сделан в ноутбуке
