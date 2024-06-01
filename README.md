# SUSTech-CSE-UG-Declaration

Template for _SUSTech CSE Undergraduate Declaration_.

## Quick Start

1. Create a new LaTeX project ([Sharelatex](https://sharelatex.cra.ac.cn/) is recommended) and upload `header.png` and `main.tex`.

2. Upload your own signature and name it as `signature.png` (all three files should be in the same folder).

3. Modify the following fields in `main.tex`:

```tex
\newcommand{\sname}{张三}  % your name
\newcommand{\sid}{12312345}  % your student ID
\newcommand{\cid}{CS109} % course ID (not mandatory)
\newcommand{\cname}{Introduction to Computer Programming}  % course name
```

4. Compile `main.tex` and you can get the PDF version of the declaration form.
