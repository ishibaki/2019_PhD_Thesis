# Ph.D. Thesis

[Latest](https://github.com/ishibaki/2019_PhD_Thesis)

---

run the following code;

```sh
pandoc -f markdown -t latex --latex-engine=xelatex -V geometry:margin=1in -V geometry:a4paper -N --template ~/.pandoc/templates/eisvogel.latex --toc -S --bibliography ~/.pandoc/library.bib --csl ~/.pandoc/apa-2.csl -V "title-logo.pdf" -V logo-width=500 -o ../PhD_Thesis.pdf ./0_pdf_metadata/*metadata.tex 1_author-info.md 2_abstruct.md 3_intro.md 4_exp-proc.md 5_result1.md 6_result2.md 7_discussion.md 8_figs-and-tables.md 9_acknowledgements.md 10_publication.md 11_citations.md
```

