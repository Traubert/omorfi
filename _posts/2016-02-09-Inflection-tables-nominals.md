---
layout: page
title: "Inflection tables nominals"
category: stats
date: 2016-02-08 18:23:58
---


# Introduction #

The classification of nominals in Finnish morphology is based on three things: the stem variations they take, the suffix variants they use and ... This page shows a table of possible suffix variants and their class numbers.

### Nominal allomorph tables ###

The nominals differ in classification on one side by the suffix allomorphs they select. The possible allomorphs apply for following cases:

  * singular partitive can be: a, ä, ta, or tä (some segmentations include also allomorphs tta, ttä, which in our case is just ta, tä attached to consonant stem)
  * singular illative can be: an, en, in, on, un, yn, än, ön, han, hen, hin, hon, hun, hyn, hän, hön, or seen
  * plural genitive can be: ien, jen, iden, itten, ten, in
  * plural partitive can be: ia, iä, ja, jä, ita, itä
  * plural illative can be: iin, ihin, isiin.

In following table, _Our ID_ is a running number that is used internally in some parts of omorfi, the _nssl_ is list of dictionary classes it applies to. The rest of the columns are the allomorphs, here plus sign ’+’ means that allomorph is regularly and normatively used, minus sign means ’-’ it is not used and would sound strange for natives, a question mark ’?’ is limited use, and a plus-minus sign ’±’ is not normative in current dictionaries, but may appear in old dictionaries, and minus-plus ’∓’ for typical sub-standard and dialectal forms that may be common enough that it needed to be implemented in our systems and is not really deemed even strange by native speakers. We have identified following combinations (this is the full table without phonemic collapsing):

| **Our ID** | _nssl_ | a | ä | ta | tä | an | en | in | on | un | yn | än | ön | han | hen | hin | hon | hun | hyn | hän | hön | seen | ien | jen | iden | itten | ten | in | ia | iä | ja | jä | ita | itä | iin | ihin | isiin |
|:-----------|:-------|:--|:---|:---|:----|:---|:---|:---|:---|:---|:---|:----|:----|:----|:----|:----|:----|:----|:----|:-----|:-----|:-----|:----|:----|:-----|:------|:----|:---|:---|:----|:---|:----|:----|:-----|:----|:-----|:------|
| 1      | 1      | + | - | -  | -  | -  | -  | -  | +  | -  | -  | -  | -  | -   | -   | -   | ∓   | -   | -   | -   | -   | -    | -   | +   | -    | -     | -   | ±  | -  | -  | +  | -  | -   | -   | -   | +    | -     |
| 2      | 1      | + | - | -  | -  | -  | -  | -  | -  | +  | -  | -  | -  | -   | -   | -   | -   | ∓   | -   | -   | -   | -    | -   | +   | -    | -     | -   | ±  | -  | -  | +  | -  | -   | -   | -   | +    | -     |
| 3      | 1      | - | + | -  | -  | -  | -  | -  | -  | -  | +  | -  | -  | -   | -   | -   | -   | -   | ∓   | -   | -   | -    | -   | +   | -    | -     | -   | ±  | -  | -  | -  | +  | -   | -   | -   | +    | -     |
| 4      | 1      | - | + | -  | -  | -  | -  | -  | -  | -  | -  | -  | +  | -   | -   | -   | -   | -   | -   | -   | ∓   | -    | -   | +   | -    | -     | -   | ±  | -  | -  | -  | +  | -   | -   | -   | +    | -     |
| 5      | 2, 4   | + | - | -  | -  | -  | -  | -  | +  | -  | -  | -  | -  | -   | -   | -   | ∓   | -   | -   | -   | -   | -    | -   | +   | +    | +     | -   | ±  | -  | -  | +  | -  | +   | -   | -   | +    | -     |
| 6      | 2      | + | - | -  | -  | -  | -  | -  | -  | +  | -  | -  | -  | -   | -   | -   | -   | ∓   | -   | -   | -   | -    | -   | +   | +    | +     | -   | ±  | -  | -  | +  | -  | +   | -   | -   | +    | -     |
| 7      | 2      | - | + | -  | -  | -  | -  | -  | -  | -  | +  | -  | -  | -   | -   | -   | -   | -   | ∓   | -   | -   | -    | -   | +   | +    | +     | -   | ±  | -  | -  | -  | +  | -   | +   | -   | +    | -     |
| 8      | 2, 4   | - | + | -  | -  | -  | -  | -  | -  | -  | -  | -  | +  | -   | -   | -   | -   | -   | -   | -   | ∓   | -    | -   | +   | +    | +     | -   | ±  | -  | -  | -  | -  | -   | +   | -   | +    | -     |
| 9      | 3      | ± | - | +  | -  | -  | -  | -  | +  | -  | -  | -  | -  | -   | -   | -   | ∓   | -   | -   | -   | -   | -    | -   | ∓   | +    | +     | -   | ±  | -  | -  | ∓  | -  | +   | -   | -   | +    | -     |
| 10      | 3      | - | ± | -  | +  | -  | -  | -  | -  | -  | -  | -  | +  | -   | -   | -   | -   | -   | -   | -   | ∓   | -    | -   | ∓   | +    | +     | -   | ±  | -  | -  | -  | ∓  | -   | +   | -   | +    | -     |
| 11      | 3      | ± | - | +  | -  | -  | +  | -  | -  | -  | -  | -  | -  | -   | ∓   | -   | -   | -   | -   | -   | -   | -    | -   | ∓   | +    | +     | -   | ±  | -  | -  | ∓  | -  | +   | -   | -   | +    | -     |
| 12      | 5      | + | - | -  | -  | -  | -  | +  | -  | -  | -  | -  | -  | -   | -   | ∓   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | -   | ±  | -  | -  | +  | -  | -   | -   | -   | +    | -     |
| 13      | 5      | - | + | -  | -  | -  | -  | +  | -  | -  | -  | -  | -  | -   | -   | ∓   | -   | -   | -   | -   | -   | +   | -  | -   | -    | -     | -   | ±  | -  | -  | -  | +  | -   | -   | -   | +    | -     |
| 14      | 6      | + | - | -  | -  | -  | -  | +  | -  | -  | -  | -  | -  | -   | -   | ∓   | -   | -   | -   | -   | -   | -    | -   | +   | +    | +     | -   | ±  | -  | -  | +  | -  | +   | -   | -   | +    | -     |
| 15      | 6      | - | + | -  | -  | -  | -  | +  | -  | -  | -  | -  | -  | -   | -   | ∓   | -   | -   | -   | -   | -   | -    | -   | +   | +    | +     | -   | ±  | -  | -  | -  | +  | -   | +   | -   | +    | -     |
| 16      | 7      | + | - | -  | -  | -  | +  | -  | -  | -  | -  | -  | -  | -   | ∓   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | -   | ±  | +  | -  | -  | -  | -   | -   | +   | -    | -     |
| 17      | 7      | - | + | -  | -  | -  | +  | -  | -  | -  | -  | -  | -  | -   | ∓   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | -   | ±  | +  | -  | -  | -  | -   | -   | +   | -    | -     |
| 18      | 8      | + | - | -  | -  | -  | +  | -  | -  | -  | -  | -  | -  | -   | ∓   | -   | -   | -   | -   | -   | -   | -    | -   | +   | -    | -     | -   | ±  | -  | -  | +  | -  | -   | -   | -   | -    | -     |
| 19      | 8      | - | + | -  | -  | -  | +  | -  | -  | -  | -  | -  | -  | -   | ∓   | -   | -   | -   | -   | -   | -   | -    | -   | +   | -    | -     | -   | ±  | -  | -  | -  | +  | -   | -   | -   | +    | -     |
| 20      | 9      | + | - | -  | -  | +  | -  | -  | -  | -  | -  | -  | -  | ∓   | -   | -   | -   | -   | -   | -   | -   | -    | -   | +   | -    | -     | -   | ±  | -  | -  | +  | -  | -   | -   | -   | -    | -     |
| 21      | 9      | - | + | -  | -  | -  | -  | -  | -  | -  | -  | +  | -  | -   | -   | -   | -   | -   | -   | ∓   | -   | -    | -   | +   | -    | -     | -   | ±  | -  | -  | -  | +  | -   | -   | -   | +    | -     |
| 22      | 10     | + | - | -  | -  | +  | -  | -  | -  | -  | -  | -  | -  | ∓   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | -   | ±  | +  | -  | -  | -  | -   | -   | +   | -    | -     |
| 23      | 10     | - | + | -  | -  | -  | -  | -  | -  | -  | -  | +  | -  | -   | -   | -   | -   | -   | -   | ∓   | -   | -    | +   | -   | -    | -     | -   | ±  | -  | +  | -  | -  | -   | -   | +   | -    | -     |
| 24     | 11     | + | - | ±  | -  | +  | -  | -  | -  | -  | -  | -  | -  | ∓   | -   | -   | -   | -   | -   | -   | -   | -    | +   | ±   | +    | +     | -   | ±  | +  | -  | ±  | -  | +   | -   | +   | +    | -     |
| 25     | 11     | - | + | -  | ±  | -  | -  | -  | -  | -  | -  | +  | -  | -   | -   | -   | -   | -   | -   | ∓   | -   | -    | +   | ±   | +    | +     | -   | ±  | -  | +  | -  | ±  | -   | +   | +   | +    | -     |
| 26     | 12     | + | - | ±  | -  | +  | -  | -  | -  | -  | -  | -  | -  | ∓   | -   | -   | -   | -   | -   | -   | -   | -    | -   | -   | +    | +     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | +    | -   n |
| 27     | 12     | - | + | -  | ±  | -  | -  | -  | -  | -  | -  | +  | -  | -   | -   | -   | -   | -   | -   | ∓   | -   | -    | -   | -   | +    | +     | -   | ±  | -  | -  | -  | -  | -   | +   | -   | +    | -     |
| 28      | 13, 14 | + | - | ±  | -  | +  | -  | -  | -  | -  | -  | -  | -  | ∓   | -   | -   | -   | -   | -   | -   | -   | -    | -   | +   | +    | +     | -   | ±  | -  | -  | +  | -  | +   | -   | -   | +    | -     |
| 29      | 13, 14 | - | + | -  | ±  | -  | -  | -  | -  | -  | -  | +  | -  | -   | -   | -   | -   | -   | -   | ∓   | -   | -    | -   | +   | +    | +     | -   | ±  | -  | -  | -  | +  | -   | +   | -   | +    | -     |
| 30     | 15     | + | - | +  | -  | +  | ±  | -  | -  | -  | -  | -  | -  | ∓   | -   | -   | -   | -   | -   | -   | -   | -    | -   | -   | +    | +     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | +    | +     |
| 31     | 16     | + | - | ±  | -  | +  | -  | -  | -  | -  | -  | -  | -  | ∓   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | -   | ±  | +  | -  | -  | -  | -   | -   | +   | -    | -     |
| 32     | 16     | - | + | -  | ±  | -  | -  | -  | -  | -  | -  | +  | -  | -   | -   | -   | -   | -   | -   | ∓   | -   | -    | +   | -   | -    | -     | -   | ±  | -  | +  | -  | -  | -   | -   | +   | -    | -     |
| 33     | 17, 44 | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | ±   | -   | -   | -   | -   | -   | -   | -   | +    | -   | -   | +    | +     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | ±    | +     |
| 34     | 17, 44 | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | ±   | -   | -   | -   | -   | -   | -   | +    | -   | -   | +    | +     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | ±    | +     |
| 35     | 17, 44 | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | ±   | -   | -   | -   | -   | -   | -   | +    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | ±    | +     |
| 36     | 17, 44 | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | ±   | -   | -   | -   | -   | +    | -   | -   | +    | +     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | ±    | +     |
| 37     | 17, 44 | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | ±   | -   | -   | -   | +    | -   | -   | +    | +     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | ±    | +     |
| 38     | 17, 44 | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | ±   | -   | +    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | ±    | +     |
| 39     | 17, 44 | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | ±   | +    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | ±    | +     |
| 40     | 18     | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | +   | -   | -   | -   | -   | -   | -   | -   | -    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | +   | -   | -   | +    | -     |
| 41     | 18     | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | +   | -   | -   | -   | -   | -   | -   | -    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | +   | -   | -   | +    | -     |
| 42     | 18, 19 | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | +   | -   | -   | -   | -   | -   | -   | -    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | +    | -     |
| 43     | 18     | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | +   | -   | -   | -   | -   | -   | -    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | +   | -   | -   | +    | -     |
| 44     | 18     | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | +   | -   | -   | -   | -   | -   | -    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | +    | -     |
| 45     | 18, 19 | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | +   | -   | -   | -   | -   | -    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | +   | -   | -   | +    | -     |
| 46     | 18     | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | +   | -   | -   | -   | +   | -   | -   | -   | -    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | +   | -   | -   | +    | -     |
| 47     | 18     | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | +   | -   | -   | -    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | +    | -     |
| 48     | 18     | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | +   | -   | -    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | +    | -     |
| 49    | 18, 19 | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | +   | -    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | +    | -     |
| 50     | 20     | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | +   | -   | -   | -   | -   | -   | -   | -   | +    | -   | -   | +    | +     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | ±    | +     |
| 51     | 20     | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | +   | -   | -   | -   | -   | -   | -   | +    | -   | -   | +    | +     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | ±    | +     |
| 52     | 20     | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | +   | -   | -   | -   | -   | -   | -   | +    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | ±    | +     |
| 53     | 20     | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | +   | -   | -   | -   | -   | +    | -   | -   | +    | +     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | ±    | +     |
| 54     | 20     | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | +   | -   | -   | -   | +    | -   | -   | +    | +     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | ±    | +     |
| 55     | 20     | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | +   | -   | +    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | ±    | +     |
| 56     | 20     | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | +   | +    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | ±    | ∓     |
| 57     | 21     | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | +   | -   | -   | -   | -   | -   | -   | -   | ∓    | -   | -   | +    | ±     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | ±    | ∓     |
| 58     | 21     | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | +   | -   | -   | -   | -   | -   | -   | ∓    | -   | -   | +    | ±     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | ±    | ∓     |
| 59     | 21     | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | +   | -   | -   | -   | -   | -   | -   | ∓    | -   | -   | +    | ±     | -   | -  | -  | -  | -  | -  | -   | +   | -   | ±    | ∓     |
| 60     | 21     | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | +   | -   | -   | -   | -   | ∓    | -   | -   | +    | ±     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | ±    | ∓     |
| 61     | 21     | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | +   | -   | -   | -   | ∓    | -   | -   | +    | ±     | -   | ±  | -  | -  | -  | -  | +   | -   | -   | ±    | ∓     |
| 62     | 21     | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | +   | -   | ∓    | -   | -   | +    | ±     | -   | -  | -  | -  | -  | -  | -   | +   | -   | ±    | ∓     |
| 63     | 21     | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | +   | ∓    | -   | -   | +    | ±     | -   | -  | -  | -  | -  | -  | -   | +   | -   | ±    | ∓     |
| 64     | 23, 40 | - | - | +  | -  | -  | +  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | -   | -  | +  | -  | -  | -  | -   | -   | +   | -    | -     |
| 65     | 23, 40 | - | - | -  | +  | -  | +  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | -   | -  | -  | +  | -  | -  | -   | -   | +   | -    | -     |
| 66     | 24, 26..30, 32, 33, 38, 39, 42 | - | - | +  | -  | -  | +  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | +   | -  | +  | -  | -  | -  | -   | -   | +   | -    | -     |
| 67     | 24, 26..30, 32, 33, 38, 39, 42 | - | - | -  | +  | -  | +  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | +   | -  | -  | +  | -  | -  | -   | -   | +   | -    | -     |
| 68     | 25     | + | - | +  | -  | -  | +  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | +   | -  | +  | -  | -  | -  | -   | -   | +   | -    | -     |
| 69     | 25     | - | + | -  | +  | -  | +  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | +   | -  | -  | +  | -  | -  | -   | -   | +   | -    | -     |
| 70     | 34     | - | - | +  | -  | +  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | +   | ±  | +  | -  | -  | -  | -   | -   | +   | -    | -     |
| 71     | 34     | - | - | -  | +  | -  | -  | -  | -  | -  | -  | +  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | +   | ±  | -  | +  | -  | -  | -   | -   | +   | -    | -     |
| 72     | 35     | - | - | +  | -  | +  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | -   | +  | +  | -  | -  | -  | -   | -   | +   | -    | -     |
| 73     | 36     | - | - | +  | -  | +  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | +   | +  | +  | -  | -  | -  | -   | -   | +   | -    | -     |
| 74     | 36     | - | - | -  | +  | -  | -  | -  | -  | -  | -  | +  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | +   | +  | -  | +  | -  | -  | -   | -   | +   | -    | -     |
| 75     | 37     | + | - | +  | -  | +  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | +   | +  | +  | -  | -  | -  | -   | -   | +   | -    | -     |
| 76     | 37     | - | + | -  | +  | -  | -  | -  | -  | -  | -  | +  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | +   | -   | -    | -     | +   | +  | -  | +  | -  | -  | -   | -   | +   | -    | -     |
| 78     | 41, 47, 48 | - | - | +  | -  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | +    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | +   | -   | -   | +    | +     |
| 79     | 41, 47, 48 | - | - | -  | +  | -  | -  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | +    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | +    | +     |
| 80     | 43     | - | - | +  | -  | -  | +  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | +   | -   | -   | +    | +     |
| 81     | 43     | - | - | -  | +  | -  | +  | -  | -  | -  | -  | -  | -  | -   | -   | -   | -   | -   | -   | -   | -   | -    | -   | -   | +    | +     | -   | -  | -  | -  | -  | -  | -   | +   | -   | +    | +     |
| **Our ID** | _nssl_ | a | ä | ta | tä | an | en | in | on | un | yn | än | ön | han | hen | hin | hon | hun | hyn | hän | hön | seen | ien | jen | iden | itten | ten | in | ia | iä | ja | jä | ita | itä | iin | ihin | isiin |