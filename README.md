# hse_hw3_chromhmm

Ссылка на colab: https://colab.research.google.com/drive/1adQQPYY-_oYupe8h-1n6V8GOwgiwdSrY?usp=sharing

Так как в таблице c CHIP-seq эксперементами не оказалось моей клеточной линии, я взяла другую - HUVEC.

**cellmarkfiletable.txt**

| Клеточная линия  | Гистоновая метка  | Файл  | Контрльный файл  |
|---|---|---|---|
| HUVEC  | H3K27ac  | H3k27acStdAlnRep1.bam   |  ControlStdAlnRep1.bam |
| HUVEC  | H2a  | H2azAlnRep1.bam  | ControlStdAlnRep1.bam  |
| HUVEC  | H3k27me3  |  H3k27me3StdAlnRep1.bam    |  ControlStdAlnRep1.bam |
| HUVEC |  H3k36me3 |  H3k36me3StdAlnRep1.bam  | ControlStdAlnRep1.bam  |
| HUVEC  | H3k4me1  | H3k4me1StdAlnRep1.bam  |  ControlStdAlnRep1.bam |
| HUVEC  |  H3k4me2 |  H3k4me2StdAlnRep1.bam    |  ControlStdAlnRep1.bam |
| HUVEC  |  H3k4me3 |  H3k4me3StdAlnRep1.bam     |  ControlStdAlnRep1.bam |
| HUVEC  | H3k79me2  | H3k79me2AlnRep1.bam    |  ControlStdAlnRep1.bam |
| HUVEC  |  H3k9ac |  H3k9acStdAlnRep1.bam   | ControlStdAlnRep1.bam   |
| HUVEC  | H3k9me1  |  H3k9me1StdAlnRep1.bam   |  ControlStdAlnRep1.bam |

Выдача ChromHMM:

![](ChromHMM/emissions_12.png)

![](ChromHMM/transitions_12.png)

![](ChromHMM/Huvec_12_overlap.png)

![](ChromHMM/Huvec_12_RefSeqTES_neighborhood.png)

![](ChromHMM/Huvec_12_RefSeqTSS_neighborhood.png)
