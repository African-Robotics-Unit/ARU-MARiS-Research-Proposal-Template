# ARU Research Proposal Template

This is a template repository for creating a research proposal for prospective African Robotics Unit students. The template is compiled by LaTeX to produce a PDF document.

> [!IMPORTANT]  
> Only use this template if you were specifically asked to do so by Robyn Verrinder. This is not an application form for the African Robotics Unit.

## How To

### Compile the PDF

There are several ways to compile the LaTeX document depending on your preferred workflow. Here are a few options:

1. [**Overleaf**](https://www.overleaf.com/)  
Download the repository as a ZIP file and upload it to Overleaf. Overleaf will automatically compile the document for you with most dependencies pre-installed, and you can download the PDF from there.
1. **Local**  
Clone the repository to your local machine and edit with your preferred text editor. You can compile the document either by using a LaTeX extension for your text editor, or by using the command `latexmk` directly. You will need to have a LaTeX distribution installed on your machine to provide the necessary packages and executables.

```bash
git clone https://github.com/African-Robotics-UNit/ARU-MARiS-Research-Proposal-Template
```

```bash
latexmk
```

<details>

1. You must install a LaTeX distribution on your machine to compile the document. The most popular distributions are [TeX Live](https://www.tug.org/texlive/) and [MiKTeX](https://miktex.org/) (among others). The specific installation instructions will depend on your operating system.

1. `latexmk` should identify read the configuration file `.latexmkrc` in the repository and compile the document accordingly. More compile options could also be added by your LaTeX extensions.

1. There are many LaTeX packages that are used in the document. If you encounter an error about a missing package, you can install it using the package manager of your LaTeX distribution.

</details>

### Edit the Proposal

The proposal consists of a series of `.tex` files. Begin in [`0_main.tex`](0_main.tex). Follow the instructions in the comments to fill in the necessary information for each section thereafter.

Once done, remember to add your signature via your preferred method. Normally you should only add your signature manually. Submit as instructed.
