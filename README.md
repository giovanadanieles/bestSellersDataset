# Best Sellers Dataset

This is a dataset of books in raw data format. The books are divided into two categories: *success* and *other*. In the first, we aggregated 110 best-selling books and, in the second, 109 books not categorized as such (at least not in the period and source considered). All 219 instances were written in the English language.
    
To address the decision of what is a best seller title, we consulted the so-called [*Publishers Weekly Bestseller Lists*](https://www.publishersweekly.com/pw/nielsen/index.html) (PWBL), first published in 1895. In it, we found 110 titles in the public domain, available for download on the [*Gutenberg Project*](https://www.gutenberg.org/) platform. Those became part of the set as instances of the *success* category.

To build the *other* class, we considered: (a) books published in the same period as the successful ones and (b) not listed as best sellers in the PWBL. More specifically, if the *success* category had eight instances published in 1923, the *other* category would have the same number of titles published in the same year — those titles randomly selected in the *Project Gutenberg* catalog. At the end of this process, we got 109 non-successful books (one less than the other category, as it was infeasible to gather the same amount of books for every considered year).

After selecting the instances, we cleaned up the texts to solely preserve the narratives' relevant content. In this manner,  elements such as the header and footer included by the *Gutenberg Project* were removed, as well as author/translator/editor notes, captions and illustrations indicators, glossaries, footnotes, side-notes, appendices, and annexes.

For additional information, please consider the following reference: **A. P. Hackett and J. H. Burke. 80 years of best sellers. R. R. Bowker Company, 1977**.
