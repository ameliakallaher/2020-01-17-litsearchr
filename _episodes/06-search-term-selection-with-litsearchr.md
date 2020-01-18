---
title: "Search term selection with litsearchr"
teaching: 
exercises:
questions:
objectives:
keypoints:
---


## Developing a good naive search

-- notes on choosing precise search terms, goal is not high recall
-- assume familiarity with PICO and its variants
-- assign work in small groups to recreate an existing review?
-- allow individual too based on expertise?
-- would be good to have an actual benchmark to test against
? could use this to get data for sensitivity analysis on naive search quality
? 10 minutes to generate a search for existing SR?
? mass testing precision and recall
? save all naive searches, expert score + PRESS for sensitivity

exercise: 
1) choose an existing review or topic, either pre-selected for data or anything
2) if pre-selected, read title/abs/objectives, and/or identify PICO
3) come up with naive search terms to match PICO
4) run searches in 2-3 databases, exporting .ris or .bib files

## Importing and deduplicating naive search results

```{r}

library(litsearchr)

```

## Extracting keywords from naive search results

- use multiple methods, compare different results (or not - rJava issues)

```{r}

```

## Identifying important keywords

- don't include grouping/decisions; next lesson

```{r}

```
