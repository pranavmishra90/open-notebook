# Key Resources Tables
Pranav Kumar Mishra
2026-02-17

Adapted from the [Cell Press STAR
Methods](https://www.cell.com/star-authors-guide) to help produce
Structured, Transparent, Accessible Reporting in research.

This page is a [living
document](https://en.wikipedia.org/wiki/Living_document) and a
work-in-progress. With the goal of improving research reproducibility,
several major journals now require a detailed listing of the key
resources required to conduct the experiments described.

Schedule permitting, I will update the “[csv
databases](https://github.com/pranavmishra90/research-reference/tree/main/lab-materials/key-resources-table)”,
which can be found on GitHub. Using Quarto and Python, the csv files are
rendered into HTML and GitHub-flavored Markdown. The markdown file is
additionally rendered in my [Wordpress
post](https://www.drpranavmishra.com/research/2023/star-methods-key-resources/).

    KeyError: 'repo_root'
    [31m---------------------------------------------------------------------------[39m
    [31mKeyError[39m                                  Traceback (most recent call last)
    [36mCell[39m[36m [39m[32mIn[1][39m[32m, line 23[39m
    [32m     20[39m     os.environ[[33m'[39m[33mis_docker[39m[33m'[39m] = [33m'[39m[33mFalse[39m[33m'[39m
    [32m     21[39m     os.environ[[33m'[39m[33mrepo_root[39m[33m'[39m] = [33m"[39m[33m/home/pranav/work/pranavmishra90/research-reference[39m[33m"[39m
    [32m---> [39m[32m23[39m os.chdir([43mos[49m[43m.[49m[43menviron[49m[43m[[49m[33;43m'[39;49m[33;43mrepo_root[39;49m[33;43m'[39;49m[43m][49m)

    [36mFile [39m[32m<frozen os>:709[39m, in [36m_Environ.__getitem__[39m[34m(self, key)[39m
    [32m    706[39m     value = [38;5;28mself[39m._data[[38;5;28mself[39m.encodekey(key)]
    [32m    707[39m [38;5;28;01mexcept[39;00m [38;5;167;01mKeyError[39;00m:
    [32m    708[39m     [38;5;66;03m# raise KeyError with the original key value[39;00m
    [32m--> [39m[32m709[39m     [38;5;28;01mraise[39;00m [38;5;167;01mKeyError[39;00m(key) [38;5;28;01mfrom[39;00m[38;5;250m [39m[38;5;28;01mNone[39;00m
    [32m    710[39m [38;5;28;01mreturn[39;00m [38;5;28mself[39m.decodevalue(value)

    [31mKeyError[39m: 'repo_root'

## Antibodies

    <>:12: SyntaxWarning: "\." is an invalid escape sequence. Such sequences will not work in the future. Did you mean "\\."? A raw string is also an option.
    <>:12: SyntaxWarning: "\." is an invalid escape sequence. Such sequences will not work in the future. Did you mean "\\."? A raw string is also an option.
    /tmp/ipykernel_2782/516824930.py:12: SyntaxWarning: "\." is an invalid escape sequence. Such sequences will not work in the future. Did you mean "\\."? A raw string is also an option.
      antibodies = antibodies.astype(str).replace('\.0', '', regex=True)

| REAGENT or RESOURCE | SOURCE | IDENTIFIER | Size (kDA) | Source | Target | RRID |
|----|----|----|----|----|----|----|
| ADAMTS4 Ab | RnD | Cat# MAB4307; RRID:AB_2222318 | 58 | Mouse | Human | [AB_2222318](http://antibodyregistry.org/AB_2222318) |
| Aggrecan Ab | RnD | Cat# AF1220; RRID:AB_2219833 | 120 | Goat | Human | [AB_2219833](http://antibodyregistry.org/AB_2219833) |
| Collagen II Ab | Abcam | Cat# ab34712; RRID:AB_731688 | 141 | Rabbit | Human | [AB_731688](http://antibodyregistry.org/AB_731688) |
| IL-1β Ab | Santa Cruz | Cat# SC-32294; RRID:AB_627790 | 17 | Mouse | Human | [AB_627790](http://antibodyregistry.org/AB_627790) |
| IL-36RA Ab | RnD | Cat# AF1275; RRID:AB_2124757 | 17 | Goat | Human | [AB_2124757](http://antibodyregistry.org/AB_2124757) |
| IL-36α Ab | RnD | Cat# AF1078; RRID:AB_2124771 | 16 | Goat | Human | [AB_2124771](http://antibodyregistry.org/AB_2124771) |
| Lubricin (PRG4) Ab | Rush U | – | – | Rabbit | Human | [–](http://antibodyregistry.org/%20--) |
| MMP13 Ab | RnD | Cat# AF511; RRID:AB_355401 | 55 | Goat | Human | [AB_355401](http://antibodyregistry.org/AB_355401) |
| SOX-9 Ab | Abcam | Cat# ab185966; RRID:AB_2728660 | 70 | Rabbit | Human | [AB_2728660](http://antibodyregistry.org/AB_2728660) |

**Note:** [RRIDs](https://scicrunch.org/resources/rin/rrids) are sourced
from the [Antibody Registry](http://antibodyregistry.org/), via
[SciCrunch](https://scicrunch.org/resources/rin/rrids)

**Acknowledgement:** We would like to acknowledge [Dr. Thomas
Schmid](https://www.rushu.rush.edu/faculty/thomas-schmid-phd) at Rush
University for preparing and sharing the Lubricin (PRG4) antibody with
our group.

## Biological Samples

| REAGENT or RESOURCE | SOURCE | IDENTIFIER |
|---------------------|--------|------------|
|                     |        |            |

## Chemicals; peptides; and recombinant proteins

| REAGENT or RESOURCE | SOURCE | IDENTIFIER | Experiment |
|----|----|----|----|
| Alcohol 100% | Sigma-Aldrich | 65347-M | Histology |
| EM-400 Embedding Medium Paraffin | Leica | 3801320 | Histology |
| HistoChoice Mounting Media | VWR | H157-475ML | Histology |
| Hydrochloric acid | Sigma-Aldrich | 258148-500ML | Histology |
| Paraformaldehyde powder 95% | Sigma-Aldrich | 158127-500G | Histology |
| Paraplast X-tra | Leica | 39603002 | Histology |
| Permount Mounting Medium | Fisher | SP15-500 | Histology |
| Reagent Alcohol 95% Histoprep | Fisher | HC13001GL | Histology |
| Tissue Path™ Disposable Embedding Rings | Fisher | 22038198 | Histology |
| Xylenes (Histological) | Fisher Chemical | X3P-1GAL | Histology |
| 10x Tris/Glycine/SDS Buffer | Bio-Rad | 1610732 | Western Blot |
| 2-Mercaptoethanol | Bio-Rad | 1610710 | Western Blot |
| 4x Laemmli Sample Buffer | Bio-Rad | 1610747 | Western Blot |
| BCA Protein Assay Kit | Pierce | 23225 | Western Blot |
| Glycine | Sigma | G-7126 | Western Blot |
| Methanol (100%) | Ficher | A412-4 | Western Blot |
| Pierce Protease and Phosphatase Inhibitor Mini Tablets EDTA-Free | Thermo | A32961 | Western Blot |
| Pierce RIPA Buffer | Thermo Scientific | 89901 | Western Blot |
| Precision Plus Protein Dual Color Standards | Bio-Rad | 1610374 | Western Blot |
| Restore Western Blot Stripping Buffer | Thermo | 21059 | Western Blot |
| SDS | Fisher | BP166-500 | Western Blot |
| Spectra Multicolor High Range Protein Ladder | Thermo Scientific | 26625 | Western Blot |
| TRIzol Reagent | Ambion | 15596018 | Western Blot |
| Tris Base | Fisher | BP154-1 | Western Blot |
| Tween-20 | Santa Cruz | SC-29913 | Western Blot |
| PowerUp SYBR Green Master Mix | Applied Biosystems | A25742 | qPCR |
| RNaseZap | Sigma | R2020-250ML | qPCR |
| SuperScript IV VILO Master Mix | Invitrogen | 11766050 | qPCR |
| TRIzol™ Reagent | Invitrogen | 15-596-018 | qPCR |
| Sodium Chloride | Fisher | S630-10 | – |

## Deposited Data

|  |  | REAGENT or RESOURCE | SOURCE | IDENTIFIER |
|----|----|----|----|----|
| A molecular single-cell lung atlas of lethal COVID-19 | GEO | GSE171524 | – | Learning |
| Cells of the adult human heart | Human Cell Atlas | DOI: 10.1038/s41586-020-2797-4 | – | Learning |

## Experimental models: Cell Lines

| REAGENT or RESOURCE | SOURCE | IDENTIFIER | Project | Purpose |
|---------------------|--------|------------|---------|---------|
|                     |        |            |         |         |

## Experimental models: Organisms and Strains

| REAGENT or RESOURCE | SOURCE | IDENTIFIER |
|---------------------|--------|------------|
|                     |        |            |

## Oligonucleotides

| REAGENT or RESOURCE | SOURCE | IDENTIFIER |
|---------------------|--------|------------|
|                     |        |            |

## Recominant DNA

| REAGENT or RESOURCE | SOURCE | IDENTIFIER |
|---------------------|--------|------------|
|                     |        |            |

## Software Algorithms

| REAGENT or RESOURCE | SOURCE | IDENTIFIER |
|---------------------|--------|------------|
|                     |        |            |

## Other

    <>:7: SyntaxWarning: "\." is an invalid escape sequence. Such sequences will not work in the future. Did you mean "\\."? A raw string is also an option.
    <>:7: SyntaxWarning: "\." is an invalid escape sequence. Such sequences will not work in the future. Did you mean "\\."? A raw string is also an option.
    /tmp/ipykernel_2782/294112252.py:7: SyntaxWarning: "\." is an invalid escape sequence. Such sequences will not work in the future. Did you mean "\\."? A raw string is also an option.
      other = other.astype(str).replace('\.0', '', regex=True)

| REAGENT or RESOURCE | SOURCE | IDENTIFIER | Experiment | Category |
|----|----|----|----|----|
| BD Vacutainer Serum | BD | 367815 | Blood test | – |
| BD Vacutainer Sodium Herparin | BD | 367878 | Blood test | – |
| HbA1c Controls | Afinion | 1115178 | Blood test | – |
| HbA1c Test Kit | Afinion | 1115015 | Blood test | – |
| Nova Max Glucose Test Strips | Nova | 43523 | Blood test | – |
| Nova Max Plus | Nova | 43436 | Blood test | Hardware |
| Gentamicin (50 mg/mL) | Glibco | 15750060 | Cell culture | Drug |
| MicroAmp EnduraPlate Optical 384-well clear reaction plate with barcode | Applied Biosystems | 4483285 | qPCR | – |
| MicroAmp Fast 96-well Reaction Plate (0.1mL) | Applied Biosystems | 4346907 | qPCR | – |
| \#10 Surgical Blade | Bard-Parker | 371110 | – | – |
