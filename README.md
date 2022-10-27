`reproducibilitysignals`

## About
The repository consists of information associated with the research on **Reproducibility** for the workshop paper *Reproducibility Signals: a preliminary analysis into studying reproducibility signals in science*. This work is a smaller part of a larger project on understanding Reproducibility in Sciences. The repository has 5 directories:
- `data/` - The directory that consists of three datasets used for the statistical tests.
- `src/` - Code, documentation, and essential information about the models built for the project.
- `scripts/` - Essential scripts necessary for setting up the project.
- `notebooks/` - Jupyter notebook(s) with sample code showcasing how to utilize the resources of the project.

## Data
TBA

## Environment
TBA

## Feature Engineering
TBA

## Results

##### Point Bi-Serial Correlation for Structural Features

| Feature | Correlation | p-value |
|---------|:------------|--------:|
| Presence of Introduction section	| 0.100109 | 0.080890 |
| Presence of Methodology section | 0.058174 | 0.311224 |
| Presence of Results section	| -0.022104 |	0.700612 |
| Number of Pages	| -0.080070 |	0.163057 |
| Number of Images |	0.052908 | 0.357125 |
| Number of Tables	| -0.020704 | 0.718750 |
| Number of Algorithms | 0.105624 | 0.065443 |
| **Number of Hyperlinks** | **0.170090** | **0.002882** |
| Number of Equations | -0.046220 | 0.421216

##### Point Bi-Serial Correlation for Linguistic Features

| Feature | Correlation | p-value |
|---------|:------------|--------:|
| Sentiment Label on the Full text | -0.032992 | 0.565988 |
| Sentiment Label on Title | 0.019568 | 0.733580 |
| Word Count | -0.035589 | 0.535794 |
| Average word length | -0.067776 | 0.237936 |
| Frequency of words greater than average word length | 0.001408 | 0.980463 |
| Number of Syllables | -0.018564 | 0.746769 |
| Number of Complex words	| 0.011650 | 0.839420 |
| Lexical Diversity (Yules-i)	| 0.091644 | 0.110201 |
| **Mean Readability** | **-0.271524** |	**0.000001** |


##### Chi-squared test on categorical features

| Feature | Chi2-value | p-value |
|---------|:-----------|--------:|
| Sentiment Label on the Full text |0.187955 | 0.664624 |
| Sentiment Label on Title | 0.036024 | 0.849466 |
| Presence of Introduction section | 2.598402 | 0.106972 |
| Presence of Methodology section | 0.794460 | 0.372755 |
| Presence of Results section | 0.030370 | 0.861653 |

##### Mann-Whitney U test on numerical data

| Feature | Statistic | p-value |
|:--------|-----------|--------:|
| **Lexical Diversity (Yules-i)**	| **11986.0**	| **0.0131** |
| Word Count | 9874.0 | 0.6547 |
| **Average word length**	| **12764.0**	| **0.0004** |
| Frequency of words greater than average word length	| 10121.5	| 0.9172 |
| Number of Syllables	| 9578.0 | 0.3911 |
| Number of Complex words	| 10234.0	| 0.9596 |
| **Mean Readability** | **7404.0** | **0.0001** |
| Number of Images	| 11111.5	| 0.2040 |
| Number of Tables | 10234.0	| 0.9586 |
| **Number of Algorithms** | **11584.0** | **0.0284** |
| Number of Pages | 9730.5 | 0.5039 |
| **Number of Hyperlinks** | **12542.0** | **0.0011** |
| Number of Equations	| 9606.0 | 0.2149 |

## License
[Creative Commons v1](https://github.com/reproducibilityproject/reproducibilitysignals/blob/main/LICENSE)

## Authors
[Akhil Pandey](https://github.com/akhilpandey95), [Hamed Alhoori](https://github.com/alhoori), [David Koop](https://github.com/dakoop)


## Citation

If you find this work useful, please cite our paper:
```bibtex
@article{akella2022WIESP,
  title={{Reproducibility Signals in Science: A preliminary analysis}},
  author={Akhil Pandey Akella and Hamed Alhoori and David Koop},
  journal={The first Workshop on Information Extraction from Scientific Publications (WIESP), AACL-IJCNLP },
  year={2022}
}
```

## Acknowledgement
This work is supported in part by NSF Grant No. [2022443](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2022443&HistoricalAwards=false).
