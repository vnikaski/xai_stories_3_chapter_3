# XAI Stories 3.0. eXplainable Artificial Intelligence for Retail Banking

ebook: https://pbiecek.github.io/xai_stories_3/

In 2020, as part of the Interpretable Machine Learning course, students created XAI Stories, an ebook that collects the experiences of the subjects covered in the form of a series of chapters on different applications of XAI techniques.

This was a great idea. Each team developed an interesting solution and then described it in a clear and interesting way. Some of these results were later presented at relevant industry conferences. In 2021 we did it again and finally we have created a separete ebook - XAI Stories 2.0.

This year we are continuing this experiment but focusing on applications in another sector - retail banking. In cooperation with students from the universities of Warsaw and Lodz, as well as partners from McKinsey and mBank, this ebook has been created - presenting various ideas and applications on how to use predictive modelling in retail, but also how to enrich these solutions with XAI.

I hope that the presented solutions will trigger development of new interesting solutions implementing explainable machine learning in the retail industry.


## How to build the book

Step 1: Clone or download the repository https://github.com/pbiecek/xai_stories_3.

Step 2: Install dependencies

```
devtools::install_dev_deps()
```

Step 3: Render the book (R commands)

```{r}
bookdown::render_book('./', 'bookdown::gitbook')
```

