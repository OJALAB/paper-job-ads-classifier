# Repository for the paper "Multilingual hierarchical classification of job advertisements for job vacancy statistics"

+ [`paper`](paper/paper-hierarchical-job-classifier.pdf)
+ [`arxiv version`](https://arxiv.org/abs/2411.03779)

## Structure

-   `codes/` 
    - raw codes for preparing the data (sampling etc)
    - processing the results
-   `figs/`
     - figures for the paper
-   `results/`:
    - results from python (`pickle` files)
    - `models-accuracy.xlsx` -- MS Excel file with results for each model
-   `paper/`
    - `job-offer-polish.pdf` / `job-offer-translated.pdf` -- CBOP job offer form
    - `paper.pdf` -- the paper
    
## Software

- The classifier is available [here](https://github.com/OJALAB/job-ads-classifier)
- Models are available [here](https://repod.icm.edu.pl/dataset.xhtml?persistentId=doi:10.18150/OCUTSI)
- Tutorial is available [here](https://colab.research.google.com/drive/1a425aagT0lczRxXPWoUlf5aFxUII37nh?usp=sharing) 

## How to cite

-   paper -- Beręsewicz, M., Wydmuch, M., Cherniaiev, H., & Pater, R. (2024). Multilingual hierarchical classification of job advertisements for job vacancy statistics. arXiv. https://arxiv.org/abs/2411.03779


```tex
@misc{beresewicz2024multi,
      title={Multilingual hierarchical classification of job advertisements for job vacancy statistics}, 
      author={Maciej Beręsewicz and Marek Wydmuch and Herman Cherniaiev and Robert Pater},
      year={2024},
      eprint={2411.03779},
      archivePrefix={arXiv},
      primaryClass={stat.AP},
      url={https://arxiv.org/abs/2411.03779}, 
}
```

-   models -- Beręsewicz, M., Wydmuch, M., Pater, R., & Cherniaiev, H. (2024). Job offers classifiers for ISCO and KZiS 2023 (Version V1) [Data set]. RepOD. https://doi.org/10.18150/OCUTSI


```tex
@data{OCUTSI_2024,
author = {Beręsewicz, Maciej and Wydmuch, Marek and Pater, Robert and Cherniaiev, Herman},
publisher = {RepOD},
title = "{Job offers classifiers for ISCO and KZiS 2023}",
year = {2024},
version = {V1},
doi = {10.18150/OCUTSI},
url = {https://doi.org/10.18150/OCUTSI}
}
```

-   data -- TBA

## Funding

Marek Wydmuch, Robert Pater and Herman Cherniaiev work was funded by the Educational Research Institute entitled: "Wspieranie dalszego rozwoju Zintegrowanego Systemu Kwalifikacji w Polsce, ZSK 6" (FERS.01.08-IP.05-0001/23).

Maciej Beręsewicz work was funded by the Polish National Agency for Academic Exchange (NAWA) under The Bekker NAWA Programme, grant number BPN/BEK/2023/1/00099/U/00001 (visit at University of Manchester between 01.06 and 31.08.2024).

[![](https://raw.githubusercontent.com/OJALAB/CBOP-datasets/main/docs/logo-nawa.png)](https://nawa.gov.pl/en/)
