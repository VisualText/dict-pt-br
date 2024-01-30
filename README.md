# dict-pt-br

Here you will find analyzers that help construct a dictionary for Brazilian Portugues.

# Wiktionary

This project takes the wiktionary file for portuguese, splits it up using a python script, and then processes the wiktionary pages for each word into a usable dicitonary for NLP++. THe objective is to create a dictionary analyzer for portuguese.

# dictkb

These are analyzers that create both dictionaries and KB files for Portuguese including numbers, states, munipalities, etc.

# Rerverso Verbs

These analyzers are from the reverso website for the 2000 most common portuguese verbs: https://conjugator.reverso.net/conjugation-portuguese-verb-ser.html

The 2000 verbs have been parsed into txt files which are located in diction/input/portverbs250.txt to portverbs2000.txt. These need to be made into an NLP++ dictionary format to be loaded using a 4th analyzer.

## Analyzers

* diction
* dictionary
* urls

## List of Abbreviations

| Abbreviation      | Meaning  |
| :---------------- | :------  |
| p              | Presente   |
| pi        | Pretérito Imperfeito   |
| pp          | Pretérito Perfeito   |
| pmp       | Pretérito Mais-que-perfeito   |
| fpt           | Futuro do Pretérito   |
| fps           | Futuro do Presente   |
| ps        | Presente do Subjuntivo   |
| pis  | Pretérito Imperfeito do Subjuntivo   |
| fs          | Futuro do Subjuntivo   |
| s                 | Singular   |
| p                 | Plural   |
| 1                 | Primeira Pessoa   |
| 2                 | Segunda Pessoa   |
| 3                 | Terceira Pessoa   |
| v                 | Verbo   |
| s               | Substantivo   |
| adj               | Adjetivo   |
| adv               | Advérbio   |
| pro               | Pronome   |
| prep              | Preposição   |
| art               | Artigo   |
| inter             | Interjeição   |
| conj              | Conjunção   |