# Tonas's $\LaTeX$ style files and template

For beautiful notes, papers, theses, and more.

## Contents

- **tonas-notes** contains beautiful colored boxed comments, environments for exercises with togglable solutions for easy handling of tutorials, assignments, tests, and course notes. Watermarked copyright footers and fancy page numberings and tasteful hyperlinks.
- **tonas-thesis** is designed for a minimalist setup with everything you need to write your thesis. If you pair this with the `ut-thesis` document class, you can effortlessly produce document compliant with the formatting requirements at the University of Toronto.
- **tonas-papers** lets you write fancy preprints to post on your website and on Arxiv with some of the above features. I will add more feautes, however all journals have their own formatting requirements, so most users are likely to prefer the first two style files.

## Installation and updates

If you use Overleaf or any local TeX editor, simply download the style file and put it into a folder called `common\` inside the root directory where your `.tex` files live.

Alternatively, if you use Git for version control, you can add this repository as a submodule to keep it up to date. Simply run this code inside your root folder:

```sh
git submodule add https://github.com/tonamatos/tonas-latex common
```

And use the following to update the style files:

```sh
git submodule update --remote
```

Once you have your desired style file, use the following line in the preamble of your `.tex` file to import the style file and use it in your documents.

```tex
\usepackage{common/tonas-thesis}
```

## Templates and demos coming soon...