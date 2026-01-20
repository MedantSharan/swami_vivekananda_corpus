# Computational Analysis of Swami Vivekananda's Complete Works

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
(DOI and License will be updated after archival)


> *"Work unto death — I am with you, and when I am gone, my spirit will work with you."* – Swami Vivekananda (Letter to Najunda Rao, 26th August 1896)

## Overview

This repository contains the **first comprehensive computational analysis** of Swami Vivekananda's Complete Works (1888-1902), applying Natural Language Processing and corpus linguistics to over **1 million words** from **975 public documents** and **762 private letters**.

**📄 For complete findings, methodology, and interpretations**: Please read [Swami_Vivekananda_Corpus_Analysis.pdf]([link-to-pdf](https://github.com/MedantSharan/swami_vivekananda_corpus/blob/main/Swami_Vivekananda_Corpus_Analysis.pdf))

This README provides a brief overview. The PDF contains the full 150+ page research narrative with detailed analysis, visualizations, and insights.

## Dataset

**Source**: [ramakrishnavivekananda.info](https://www.ramakrishnavivekananda.info/vivekananda/complete_works.htm)

- **Public Corpus**: 975 documents (lectures, writings, treatises) — over 1 million words
- **Private Corpus**: 762 epistles (letters, telegrams) with parsed structure (body, signature, postscript)
- **Time Period**: 1888-1902
- **Languages**: Primarily English, with Bengali, Sanskrit, Hindi, French
- **Geographic Coverage**: India, America, England, and other locations

All data sourced from publicly available materials. Swami Vivekananda's works are in the public domain. The datasets constructed are included in this repository.

## Key Findings (Summary)

### Part 1: Public Corpus Analysis

1. **The 1897-99 Collapse**: Quantitative documentation of dramatically reduced public output during the organizational founding period in India.

2. **Location-Based Pedagogy**: Statistical evidence that Swamiji systematically adapted his message by geography (profile switching).

3. **Topic Modeling and PCA**: PCA revealed a perfect geometry in 10-D document space, indicating governance by a small number of dominant archetypes.

4. **Topic Evolution**: LDA for topic modelling and finding topical patterns time, geography, audience etc.

5. **Sri Ramakrishna Mentions**: Patterns in how Sri Ramakrishna is mentioned in lectures and discourses, along with devanagri/sanskrit usage patterns.

6. **Outlier Detection**: Statistical methods to identify outlier talks/speeches/lectures and interpreting reasons.



### Part 2: Private Corpus Analysis

1. **Signature Patterns**: Hundreds unique signatures identified, with recipient-specific patterns showing contextual code-switching.

2. **Correspondence Timelines**: Tracking all of Swamiji's major correspondents temporally using letter frequency to visualize evolution of relationships.

3. **PCA and Relationship Trajectory**: PCA interpretation to model categories of letters and tracking relationship with recipient over time

4. **Temporal Evolution**: Chronological analysis showing how letter length, complexity, signatures and postscript usage evolved across Swamiji's active years.

5. **Semantic Clustering**: Embeddings along with UMAP projections revealing four distinct letter types based on content, with geographical and temporal patterns.

6. **Editorial Redactions**: Computational detection of 13 redacted recipient names in published letters, opening questions for biographical research.

7. **Epistolary Networks**: Network analysis showing various patterns like co-mentions, cross-mentions and bridge-building between east and west. 
   
8. **Sri Ramakrishna Mentions**: Patterns in how Swamiji refers to Sri Ramakrishna in his private correspondences, along with sanskrit usage analysis. 

**→ Full details, visualizations, and analysis in [Swami_Vivekananda_Corpus_Analysis.pdf]**

## Computational Methods Used

This analysis employed:

- **TF-IDF Analysis** - Distinctive vocabulary by location and time
- **Topic Modeling (LDA)** - Hidden thematic structure discovery
- **N-gram Analysis** - Collocation patterns and phrasal signatures
- **PCA & UMAP** - Dimensionality reduction and visualization
- **Network Analysis** - Co-mention patterns and correspondence networks
- **Semantic Embeddings** - Embeddings-based similarity analysis
- **Syntactic Complexity Metrics** - Sentence structure and elaboration patterns 
- **Outlier Detection** - Isolation forests, centroid distance etc. for statistical identification of outliers

All methods are detailed with code in the notebooks and explained in the research document.

## Repository Structure

This repository contains all computational notebooks used in the analysis. The notebooks are organized by corpus type (public/private) and analysis method. **All notebooks are referenced and explained in the main PDF document.**

All the data used is given in the **datasets** directory. Check the first cell of each notebook to see which dataset it requires.

The notebooks are **exploratory and informal** - they reflect the authentic research process, including trial and error, iterations, and discovery. They are not production code.

## Important: About These Notebooks

### What these notebooks are:
- Evidence of computational methods used
- Transparent documentation of analytical decisions
- Proof of how insights were reached
- Exploratory analysis preserving the research journey
- Originally developed and executed in Google Colab

### What these notebooks are NOT:
- Ready-to-run production code
- Optimized for linear execution by others
- Guaranteed to run end-to-end without modification
- A software package or library

**The notebooks are provided for transparency and methodological verification.** They show *how* the insights were reached, not as ready-to-use tools.

### If You Want to Understand the Analysis

1. **Read the PDF first** - It contains the complete narrative with context
2. **Refer to specific notebooks** - The PDF references which notebooks produced which findings
3. **Use notebooks as reference** - Adapt methods for your own research rather than running verbatim

### If You Want to Run These Notebooks

- Open in Google Colab (recommended original environment)
- Install dependencies as needed (usually none are required)
- Check the first cell to see which csv file is required and upload that in the session.
- Expect to see errors due to missing variables
- Expect to modify data paths and intermediate steps
- Some notebooks reference data files or session state from previous runs
- Use as methodological inspiration rather than turnkey execution

## Computational Environment

- **Platform**: Google Colab (cloud-based Jupyter notebooks)
- **Python Version**: 3.10+
- **Key Libraries**: transformers, sentence-transformers, scikit-learn, gensim, pandas, numpy, matplotlib, seaborn, plotly, networkx, beautifulsoup4

Specific versions and setup details are in individual notebooks.

## Significance

This research demonstrates:

1. **Methodological Innovation**: First large-scale computational analysis of Swami Vivekananda's corpus
2. **Pedagogical Insights**: Quantitative evidence of Swamiji's adaptive teaching strategies
3. **Structural Discovery**: Mathematical patterns (like the Triangle) revealing deep organizational principles
4. **Biographical Contributions**: New findings (redactions, correspondence patterns) for scholarly investigation
5. **Digital Humanities Model**: Showing how computational methods can illuminate spiritual literature without reductionism

## Citation

If you use this work in your research, please cite:

**For the research findings:**
```bibtex
@techreport{vivekananda_corpus_2025,
  title={Computational Analysis of Swami Vivekananda's Complete Works: 
         Revealing Structure in Sacred Literature Through Natural Language Processing},
  author={[Medant Sharan]},
  year={2026},
  institution={Independent Research},
  doi={10.5281/zenodo.XXXXXXX},
  url={https://zenodo.org/record/XXXXXXX}
}
```

**For the code/notebooks:**
```bibtex
@software{vivekananda_notebooks_2025,
  title={Exploratory Computational Notebooks for Swami Vivekananda Corpus Analysis},
  author={[Medant Sharan]},
  year={2026},
  publisher={GitHub},
  version={v1.0},
  doi={10.5281/zenodo.YYYYYYY},
  url={https://github.com/[yourusername]/vivekananda-corpus-analysis}
}
```

See [CITATION.cff](CITATION.cff) for machine-readable citation metadata.

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

You are free to:
- **Share** — copy and redistribute the material
- **Adapt** — remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit and indicate if changes were made

**Source Materials**: Swami Vivekananda's works are in the public domain. This analysis adds computational interpretation and is shared openly for research and education.

## Acknowledgments

This project emerged through devotional inquiry into the life and teachings of Swami Vivekananda. Gratitude to:

- The **Ramakrishna Math and Mission** for preserving and disseminating these teachings
- The maintainers of **ramakrishnavivekananda.info** for their excellent digital archive
- The **open-source NLP community** for the tools that made this analysis possible

The analysis was undertaken with reverence for the source material and the understanding that computational methods can reveal patterns while honoring the spiritual depth of the original works.


## Contact & Feedback

For questions, corrections, or collaboration:
- **GitHub Issues**: [Open an issue](https://github.com/[yourusername]/vivekananda-corpus-analysis/issues)
- **Email**: [medsharanofficial@gmail.com]

## Version History

- **v1.0** (January 2026): Initial release of exploratory notebooks and research document

---

**Note**: This is a living research project. While the current notebooks reflect the exploratory phase, future versions may include cleaned reproduction scripts, additional analyses, or expanded datasets. Check back for updates.

---

*This project demonstrates how computational methods can reveal patterns in spiritual and philosophical literature that would be difficult to detect through traditional reading alone, while respecting the depth and significance of the original works.*
