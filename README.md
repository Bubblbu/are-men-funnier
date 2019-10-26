# Questioning: Are men really funnier than women?

> A quick procrastinary exploration of gender biases in comedy films in response to doi:[10.1016/j.jrp.2019.103886](https://doi.org/10.1016/j.jrp.2019.103886)

This repository explores comedy films and the gender distributions of directors, writers, and actors involved. All data available and results have been thrown together in a few hours as as reaction to this [Reddit thread](https://www.reddit.com/r/science/comments/dnccrv/there_is_a_stereotype_that_men_are_funnier_than/).

The linked interview with one of the authors can be found [here](https://www.psychologytoday.com/au/blog/humor-sapiens/201910/are-men-really-funnier-women). The original article can be found [here](https://www.sciencedirect.com/science/article/abs/pii/S0092656619301072?via%3Dihub) (and is obviously paywalled).

While I won't be commenting on the study design and results per se, there has been a particular part in the interview that I found problematic:

> Why would men have higher humor ability than women on average? It is possible that the view that women are less funny is so pervasive that societal forces discourage girls and women from developing and expressing their humor, making a woman less likely to be perceived as funny. **There is, however, minimal evidence to support the view that our society suppresses women from producing and exhibiting humor.** (emphasis mine)

Omitting or even disregarding the cultural and societal dimensions of humor in a gendered study of the so-called Humor Producation Ability (HPA) seemed inappropriate to me. Thus, *this small project aims to explore one possible approach to study how a commercial, mainstream idea of humor might be subject to gender biases.*

## Instructions

`data-collection.ipynb` collects data from several manually curated lists of top comedy films according to IMDb. More information can be found in the notebook.

`are-men-funnier.ipynb` contains a few very preliminary explorations of the data.

## License & Reuse

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## Acknowledgments

This project relies on:

- [IMDbPY](https://github.com/alberanid/imdbpy) to retrieve metadata from IMDb
- [gender-guesser](https://github.com/lead-ratings/gender-guesser) to guess the gender based on first names