## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/bkhandrosov/Boris/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

Pizdets gazirovaniy
---
title: "Check me out"
---

Hello, Website!

For more information about simple R Markdown websites, please read the documentation at https://bookdown.org/yihui/rmarkdown/rmarkdown-site.html.

Please also note that simple R Markdown sites are _not_ based on **blogdown**. They are probably good for websites with only a few Rmd documents. For larger-scale and more sophisticated websites (such as blogs), you may want to use **blogdown** instead: https://github.com/rstudio/blogdown.

library(plotly)
#install.packages("quantmod")
library(quantmod)
library(xlsx)


getSymbols(c("NLY"),src='yahoo')

# basic example of ohlc charts
df <- data.frame(Date=index(NLY),coredata(NLY))

df<- df[df$Date>'2018-01-01',]
df <- df[c(TRUE,rep(FALSE,5)), ] #this picks weekly prices rather than da

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

W?
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/bkhandrosov/Boris/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
