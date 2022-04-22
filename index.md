## Welcome to my new website

这个网站采用的主题是Hacker theme

这个是我已经fork过的正在学习的仓库[repository](https://github.com/facelessmans/missing-semester)

### Show the code in homework

下面我用markdown展示一下这次课程作业的部分代码

```markdown
paper.pdf: paper.tex plot-data.png
	pdflatex paper.tex

plot-%.png: %.dat plot.py
	./plot.py -i $*.dat -o $@

。PHONY: clean
clean:
	rm *.pdf *.aux *.log *.png
	#git ls-files -o | xargs rm -f
```

由于篇幅有限，对于作业代码的展示就到这里

### Jekyll Themes

下面的英文是关于网站主题的一些介绍

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/facelessmans/forlab.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

这里提供了当遇到问题时，需要的帮助信息

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
