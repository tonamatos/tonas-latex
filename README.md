# Tonas's $\LaTeX$ style files and template

For beautiful notes, papers, theses, and more.

## Installation and updates

If you use Overleaf or any local TeX editor, simply download the style file and put it into a folder called `common\` inside the root directory where your `.tex` files live.

Alternatively, if you use Git for version control, you can add this repository as a submodule to keep it up to date. Simply run this code inside your root folder:

```sh
git submodule add https://github.com/tonamatos/tonas-latex common
```

And use the following to update the style file:

```sh
git submodule update --remote
```

Once you have the style file, use the following line in the preamble of your `.tex` file to import the style file and use it in your documents.

```tex
\usepackage{common/tonas-thesis}
```

## Templates and demos coming soon...