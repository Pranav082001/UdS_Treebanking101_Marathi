# Summary

The Marathi-Discourse treebank is a manually annotated corpus in Marathi (Devanagari script)

# Introduction

UD Marathi-Discourse is a manually annotated treebank for Marathi, consisting of sentences from a political (speech) discourse. The data is sourced from the official Marathi translation of Prime Minister Narendra Modi’s address to the nation regarding the COVID-19 pandemic, delivered on May 12, 2020.

The corpus contains 35 Discourse sentences. 
Treebank metadata also includes translation and transliteration of all the sentences. The trasnlations were perfroemd using Google translate while the transliterations were generated using Indic-Transliteration library. 
Annotations follows the Universal Dependencies v2 guidelines for tokenization, part-of-speech tags, and dependency relations.

Data was collected from the official site of Prime minister of India. Link: https://www.pmindia.gov.in/mr/news_updates/पंतप्रधानांचे-देशाला-उद्

# Acknowledgments

The treebank was annotated by Pranav Kushare. Supervision and revision by Luigi Talamo, Annemarie Verkerk, Helena Vaz.




## References

* (citation)

```
@misc{googletrans,
  author = {Suhun Han},
  title = {Googletrans: Free and Unlimited Google translate API for Python},
  year = {2020},
  publisher = {PyPI},
  howpublished = {\url{https://pypi.org/project/googletrans/}},
}
```
```
@misc{indic_transliteration,
  author = {{Vishvas Vasuki}},
  title = {indic-transliteration: Python package for Indic script transliteration},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/indic-transliteration/indic_transliteration_py}},
  note = {Version 2.3.75}
}
```

```
@misc{modi_speech_2020,
  author = {{Prime Minister's Office, India}},
  title = {पंतप्रधानांचे देशाला संबोधन (Address to the Nation on COVID-19 and Atmanirbhar Bharat)},
  year = {2020},
  month = {May 12},
  howpublished = {\url{https://www.pmindia.gov.in/mr/news_updates/पंतप्रधानांचे-देशाला-उद्/}}
}
```

* 2026-05-15 v2.18
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.18
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: agriculture, grammar, general, tourism
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Kushare, Pranav; Talamo, Luigi; Verkerk, Annemarie; Vaz, Helena
Contributing: here
Contact: annemarie.verkerk@uni-saarland.de
===============================================================================
</pre>
