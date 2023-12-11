# Website sources for Applied Machine Learning for Tabular Data


Welcome! This is a work in progress. We want to create a practical guide to creating quality predictive models from tabular data. We'll publish materials here as we create them and welcome community contributions in the form of discussions, suggestions, and edits. 

We also want these materials to be reusable and open. The sources are in the source [GitHub repository](https://github.com/aml4td/website) with a Creative Commons license attached (see below).

Our intention is to write these materials and, when we feel we're done, pick a publishing partner to produce a print version.

The book takes a holistic view of this process and focuses on a few areas that are usually left out of similar works. For example, the effectiveness of the model can be driven by how the predictors are represented. We tightly couple feature engineering methods with machine learning models. Also, quite a lot of work happens after we have determined our best model and created the final fit. Post-modeling activities are also described here. 

To cite this work, we suggest: 

```bib
@online{aml4td,
  Author = {Kuhn, M and Johnson, K},
  title = {{Applied Machine Learning for Tabular Data}},
  year = {2023},
  url = { https://aml4td.org},
  urldate = {2023-11-20}
}
```

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="premade/cc-by-nc-sa.png" /></a>

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/"). Our goal is to have an open book where people can reuse and reference the materials but can't just put their names on them and resell them (without our permission). 

## Intended Audience

Our intended audience is data analysts of many types: statisticians, data scientists, laboratory scientists, and anyone else who needs to create a model for prediction. We don't expect readers to be experts in these methods or the math behind them. Our approach is applied. We want readers to have intuition about what are good and bad ideas for their data and what to look out for. 

Some background in modeling and statistics is required. Having seen or used basic regression models is good, and understanding basic statistical concepts, such as variance, correlation, populations, samples, etc., is needed. There is some mathematical notation, so you'll need to be able to read those. There are a few more statistically sophisticated sections, but these are not pivotal topics. 

If you want a more theoretical treatment of machine learning models, we recommend Hastie et al. (2017). Other books for learning more about machine learning are Bishop and Nasrabadi (2006), Arnold et al. (2019) and, for more of a deep learning focus, Goodfellow et al. (2016).

## Is there code? 

We definitely want to decouple the content from specific software. [One of our other books](http://appliedpredictivemodeling.com/) on modeling had computing sections. They are nice to peruse, and people enjoyed having them there. However, they can quickly become outdated and take up a lot of space. 

The sources for the material use R, and early adopters can find them in the [GitHub repository](https://github.com/aml4td/website). 

However, we will create other websites with computing supplements for R and Python (hopefully more in the future). Those will become finalized around the time we finish the first version of the materials. 

## How can I ask questions? 

If you have questions about the content, it is probably best to ask on a public forum, like [cross-validated](https://stats.stackexchange.com/). You'll most likely get a faster answer there if you take the time to ask the questions in the best way possible.   

If you want a direct answer from us, you should follow what I call [_Yihui's Rule_](https://yihui.org/en/2017/08/so-gh-email/): add an issue to GitHub (labeled as "Discussion") first. It may take some time for us to get back to you. 

If you think there is a bug, please [file an issue](https://github.com//aml4td/website/issues). 

## Can I contribute? 

There is a [contributing page](https://github.com/aml4td/website/blob/main/chapters/contributing.qmd) with details on how to get up and running to compile the materials (there are a lot of software dependencies) and suggestions on how to help. 

If you just want to fix a typo, you can make a pull request to alter the appropriate `.qmd` file. 

Please feel free to improve the quality of this content by submitting **pull requests**. A merged PR will make you appear in the contributor list. It will, however, be considered a donation of your work to this project. You are still bound by the conditions of the license, meaning that you are **not considered an author, copyright holder, or owner** of the content once it has been merged in.