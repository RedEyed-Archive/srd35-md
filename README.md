# srd35-md

The SRD3.5, converted to Markdown that's rendered with [mdbook](https://github.com/rust-lang/mdBook).

In the past people making SRD based games have usually put out their content in PDFs, using LaTeX or other programs.
With the proliferation of phones and tablets, PDFs have become a not-so-great format to use.
By using markdown and then `mdbook` to render that into HTML, the final output can be much more screen-size agnostic.

Also, markdown is an extremely easy format to edit.
Hopefully, by using markdown as the source format, more people will able to make their own SRD variations by simply forking this repo.

## Project Status

Very Incomplete!

All of the RTF files had the text and tables extracted by the automatic conversion,
so there's *partial* markdown even for the parts that aren't in the actual Table of Contents for the book.
This is all in the `book_src/unsorted/` folder.

However, theres two main catches:

1) The tables were extracted imperfectly, so they need fixing up to have the proper header line and proper column layout.
2) The text was extracted without any bold/italic, section heading, or bulleted/numbered list formatting.

If you want to help out with the touch ups and organization work PRs are open.

The overall book is compiled with `mdbook`,
but that's not really required to just edit the markdown files for a PR.
