# UNLV Political Science Department Letterhead in `LaTeX`

This repository contains the UNLV Political Science Department letterhead in `LaTeX` format. The letterhead is based on the official UNLV letterhead, which is originally in Microsoft Word format.

I've left plenty of comments in the `LaTeX` file to help you customize the letterhead to your needs.

## Usage

The cover letter is based on the `moderncv` package, which is a great `LaTeX` library for creating professional-looking resumes, cover letters, and CVs. However, notice that I included some of the .sty and .cls files from the `moderncv` package in this repository. This is because I made some modifications to the original to better fit the UNLV letterhead and because I wanted to customize it for my own needs. If you want to use the original `moderncv` package, odds are this method won't work because of a few formatting issues that'll arise.

With that out of the way, here's what this repository contains:

- `cover_letter.tex`: The main `LaTeX` file that contains the letterhead. This is the file you'll want to compile.
- `cover_letter.pdf`: The compiled PDF file.
- `letterhead.pdf`: This PDF file is a converted version of the original UNLV letterhead, which was in MS Word format.
- `moderncv.cls`: The modified `moderncv` class file.
- `moderncvcolorblack.sty`: I only included the black style because that's the one I used. You can find the other styles in the original `moderncv` package.
- `moderncvcompatibility.sty`: The compatibility file. I don't think I touched this one.
- `moderncvstylebanking.sty`: The modified banking style file. There's a bunch of other styles in the original `moderncv` package, but this is the one I liked the most, so I only modified this one. If you'd like to use a different style, you'll have to modify the corresponding style file.

The `cover_letter.tex` file contains a bit of code in the preamble that sets the background to the `letterhead.pdf` document, which was by far the easiest solution I found to include the letterhead in the cover letter. The rest of the code is pretty straightforward `LaTeX` code that you can modify to your needs.

For reference, I compiled everything here using TeX Live 2024 on Mac OS X using VS Code with the `LaTeX` Workshop extension. I didn't test this in Overleaf or any other `LaTeX` editor, but I imagine it'll likely work just fine.
