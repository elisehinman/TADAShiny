---
name: Question
about: Ask a question
title: ''
labels: question
assignees: ''
editor_options: 
  markdown: 
    wrap: 72
---

**What is your question?**

A clear and concise description of the question.

**To Reproduce**

Include the Water Quality Portal data query inputs entered on the Load
data tab:

If possible, narrow down the question to a specific dataset and
`TADAShiny`tab or function:

``` r
library(TADAShiny)
# Data used 
df <- TADAdataRetrieval("a","b","c","d")

# Function your question pertains to
df <- TADA_QuestionableFunction("a","b","c","d")
```

**Expected behavior**

A clear and concise description of what you expected to happen.

**Screenshots**

If applicable, add screenshots to help explain your problem.

**Session Info**

Please include your session info:

``` r
sessionInfo()
#OR preferred:
devtools::session_info()
```

**Additional context**

Add any other context about the problem here.
