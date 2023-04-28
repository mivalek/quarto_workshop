# Intro to literate programming with Quarto
Workshop for InfAR @ Bauhaus-Universität Weimar

Here you can find the materials for the workshop. To use them, you should install [Quarto](https://quarto.org/docs/get-started/), the framework this workshop is based around (Step 1), as well as [VS Code](https://code.visualstudio.com/download) along with the [Quarto extension](https://marketplace.visualstudio.com/items?itemName=quarto.quarto) (Step 2).

You are encouraged to clone/download this folder, open it in VS Code and render the `.qmd` files as HTML (or other formats to see what happens). Since the `quarto_intro.qmd` file contains both `R` and Python code, you need to have both installed on your computer before you can render the document. You will aslo need the `R` packages `dplyr` and `kableExtra`, which can be installed in `R` with:

```r
install.packages("dplyr")
install.packages("kableExtra")
```

As for Python, you'll need Jupyter as well as the libraries `matplotlib`, `pandas`, and `seaborn`. These can be installed from the command line/terminal using `pip`:

```bash
pip install notebook matplotlib pandas seaborn
```

If you're using `conda`, I'm sure you know how to install packages in it. I don't...

Have fun!
