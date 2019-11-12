# Data Visualization

### [Lex et al. (2014)](https://doi.org/10.1109/TVCG.2014.2346248)

##### Title: UpSet: Visualization of Intersecting Sets

##### Authors: Alexander Lex, Nils Gehlenborg, Hendrik Strobelt, Romain Vuillemot, and Hanspeter Pfister

In this paper, the authors introduced **UpSet** - a novel visualization technique for quantitative analysis of sets, their intersections, and aggregates of intersections. The visualization of set-related tasks is both important and non-trivial. UpSet was designed to address these tasks and supports 23 out of 26 tasks identified by the previous state-of-the-art methods proposed by Alsallakh et al [1]. The web-based demo is in [here](https://vcg.github.io/upset/). And the video introduction is [here](https://www.youtube.com/watch?v=-IfF2wGw7Qk), which I think is really helpful.

I started by merely reading the paper, and found it hard to follow because the first two sections of this paper are about motivation and design ideas which I'm not familiar with or even realized before. I doubted it a lot because I thought manipulating set in both R and Python is quite easy. And their visualization seemed very complex and redundant to me. However, I gradually understand that the key to their work is really to provide a user-friendly interface, which can provide analysis on-the-fly. I think the tool is intuitive once you go over it and understand how to use it. And it is really good for exploratory data analysis.

##### Reference:

[1] Alsallakh, Bilal, et al. "Visualizing sets and set-typed data: State-of-the-art and future challenges." (2014): 1-21.