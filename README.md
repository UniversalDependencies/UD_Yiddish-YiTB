# Summary

YiTB is a treebank of linguistically annotated Yiddish data in the Universal Dependencies framework, created via a bootstraping machine learning method. A total of 27,872 tokens are currently in the treebank from a variety of sources and textual genres.

# Introduction

Yiddish is classified as a West Germanic language, although it includes many elements from Semitic and Slavic languages as well. It is written in a modified Hebrew alphabet. Yiddish is structurally similiar to German, but it also consists of many interesting structures not found in other Germanic languages, such as periphrastic verbs. 

There are a total of 27,872 tokens in the treebank. Roughly 60% of these stem from the Tatoeba source and consist of short sentences provided by both native and non-native speakers of Yiddish. It must be noted that there are occasional grammatical errors in these sentences, such as the use of the auxiliary _zayn_ 'be' instead of _hobn_ 'have' in past tense constructions of periphrastic verbs formed with the verb _zayn_, as well as incorrect syntax of periphrastic verbs which do not follow the typical order expected of an SVO language like Yiddish. This appears to be a common mistake of intermediate L2 Yiddish speakers. The remainder 40% of tokens stem from a variety of native speaker texts and genres. The various texts and genres are shown below. 

Lemmas, transliterations into Latin script and translations are provided as well by self-made models but are not 100% accurate. The transliteration model, which can be accessed [here](https://huggingface.co/shoowadoo/galkhesnet), was trained on wiktionary and transliterated Bible data. The translation model was trained on Tatoeba sentences and parallel Bible verses and is accessible [here](https://huggingface.co/shoowadoo/m2m100-finetuned-yi-to-en_418M_2). The lemmatization model was trained on wiktionary data and can be found [here](https://huggingface.co/shoowadoo/yiddish-lemmas). Morphological features are not included at this time. 

| Source | Author | Genre | Added |
|-----------|----------|-------|-------|
| tatoeba.org   | Various     | grammar/learner   | 2.17  |
| Book of Exodus    | Yehoyesh translation     | bible | 2.17  |
| Beethoven's Moonlight Sonata | Shloyme Bas­tom­s­ki     | fiction | 2.17  |
| Yiddish proverbs   | Various     | proverb | 2.17  |
| Haggadahs and Elijah the Prophet | Proste Yiddish    | web   | 2.17  |
| Bulletin No. 3: At the Border | Various   | nonfiction  | 2.17  |
| A Story with a Cat and Yiddish Dialects | Proste Yiddish  | web | 2.17  |
| Sholem Aleichem      | Proste Yiddish     | web | 2.17  |
| Hirshke Glik   | Shmerke Kaczerginski     | nonfiction | 2.17  |
| Book of Proverbs | Yehoyesh translation    | bible   | 2.17  |
| Shavuot and an Old Joke | Proste Yiddish   | web  | 2.17  |
| Bankrupt | Katie Brown  | fiction | 2.17  |
| Jews and Yiddish      | Nokhem Shtif      | nonfiction | 2.17  |
| Fathers and Children      | Chaim Malitz      | nonfiction | 2.17  |
| Wikipedia      | Various       | nonfiction | 2.17  |
| A Foolish Child      | Jacob Dinezon      | fiction | 2.17  |
| From the Land of Consumption      | Shloyme Gilbert      | fiction | 2.17  |
| The Four Questions      | Traditional      | liturgical | 2.17  |
| A Bit of Clarity and Simplicity Regarding the Language Question | Hillel Zeitlin      | nonfiction | 2.17  |
| Song of Songs      | Yehoyesh translation      | bible | 2.17  |


# Acknowledgments

To the best of our knowledge, the source texts used for the creation of this treebank are either in the public domain or are an orphan work for which no copyright holder can be found. If you hold the copyright to any of the texts used in this treebank and would like their removal, please contact us at the email below. 

# Changelog

* 2025-05-15 v2.17
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.17
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: grammar-examples learner-essays bible wiki fiction nonfiction spoken web
Lemmas: automatic
UPOS: manual native
XPOS: not available
Features: not available
Relations: manual native
Contributors: Andrews, Kirk
Contributing: here
Contact: m.kirkandrews@gmail.com
===============================================================================
</pre>
