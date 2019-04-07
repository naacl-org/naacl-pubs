---
layout: default
title: General *ACL instructions for camera-ready paper submissions
---

Below are the general *ACL policies for preparing camera-ready papers. Please be advised that your conference may have some differences from what is listed in this document. If you are unsure, email your conference publication chairs.

-  [Entering metadata](#entering-metadata)
-  [When and where do I send my final camera-ready paper?](#when-and-where-do-i-send-my-final-camera-ready-paper)
-  [I'm having a font/unicode issue.](#im-having-a-fontunicode-issue)
-  [How should the final copy differ from the original submission?](#how-should-the-final-copy-differ-from-the-original-submission)
-  [How long can it be?](#how-long-can-it-be)
-  [What's the deal with including an Appendix? Do I include it as supplemental?](#whats-the-deal-with-including-an-appendix-do-i-include-it-as-supplemental)
-  [What is the format for the camera-ready copy?](#what-is-the-format-for-the-camera-ready-copy)
-  [How do I ensure that my file is correctly formatted?](#how-do-i-ensure-that-my-file-is-correctly-formatted)
-  [What if my paper includes graphics?](#what-if-my-paper-includes-graphics)
-  [What about copyright?](#what-about-copyright)
-  [What if my paper's title or author list has changed?](#what-if-my-papers-title-or-author-list-has-changed)
-  [My question isn't answered here...?](#my-question-isnt-answered-here)

# Entering metadata

The metadata (title, author, abstract) that you enter into START is
very important, because it is used on the conference website,
handbook, mobile app, and the [ACL
Anthology](http://www.aclweb.org/anthology/) (and propagates to
Google Scholar, etc).

![Picture of Softconf user info fields](assets/images/userinfo.png)

Before the metadata is entered, please have all authors ensure that
the their name in their START profile (User Console &rarr; Update
Profile) appears exactly the way that they want it to appear.

* Unicode (UTF-8) can be used for accented or special characters.

* Ordinarily, names are **not** written in all caps or all lowercase.

* The "Last Name" is the name(s) by which your paper is to be
  cited. It is usually a family name, even for authors from
  cultures where the family name is written first.

* The "First Name" is usually a given name or names, including
     middle names/initials.

When entering the metadata, **please** use the lookup mechanism to
search for your co-authors' names by account ID. This links the
paper to their START account and, crucially, takes their preferred
name formatting for the metadata. If you enter the authors' names
manually, it will be more work for you, and you might introduce
errors.

The metadata should be written using Unicode (UTF-8) with LaTeX
commands. Please try to follow these guidelines:

 - In titles, please capitalize the first word, the first word
   after a colon (`:`), and all other words except the following
   "little words": articles, prepositions, coordinating
   conjunctions, and the infinitive marker "to." This includes
   hyphenated words like `Mixed-Case`.

 - BibTeX (in many bibliography styles, including ACL's) lowercases
   the titles of conference papers, and needs to be told which letters
   _not_ to lowercase. So if your title has letters that should always
   be capitals, please protect them with curly braces, like this:
   `{E}nglish`, `{C}homsky`, `{IBM}`, `{CFG}s`, `{HMM}s`. Please also
   protect the first letter after a sentence-final punctuation
   mark. For example:

   ```
   Can {LSTM} Learn to Capture Agreement? {T}he Case of {B}asque
   Named Entity Extraction from Noisy Input: Speech and {OCR}
   ```

   These curly braces will _not_ appear in the online conference
   program or proceedings. They will only appear in the BibTeX file
   that others will use to cite your paper.

 - If you need literal curly braces, please escape them like this:
   `\{` `\}`

 - Please don't use any nonstandard LaTeX commands, and there should
   be no `\footnote`s or citations using `\cite` or related commands.

 - You can use LaTeX math mode where appropriate: `An $O(n^2)$
   Algorithm for $n$-gram Smoothing`.

 - You can use Unicode (UTF-8) for accented or special characters.

 - If you copy-and-paste from your PDF file, please be sure to
   rejoin words broken by hyphenation.

#  When and where do I send my final camera-ready paper?

   You may submit the final
   version of your paper by
   navigating to your conference START login, e.g., [https://www.softconf.com/naacl2019/papers](https://www.softconf.com/naacl2019/papers)
   and following the internal links. You should have received an email
   with more information about this procedure.

#  How should the final copy differ from the original submission?

   The camera-ready version of your paper should incorporate the
   comments of the reviewers as well as other changes you see fit to
   make. In addition, be sure to do all of the following:

   - Include the authors' names and affiliations under the title.
   - De-anonymize references to your own work in the body of the paper.
   - Where appropriate, add acknowledgments for colleagues, reviewers, and grants. Do not number the Acknowledgements section.
   - Ensure that all tables, graphs, and figures are readable when
     viewed in black and white (to help the color-blind and those
     reading print-outs).
   - Verify that you are following your conference style guidelines (e.g., font sizes, placement of captions)
   - Be sure not to override the default caption size packages.
   - If you are including an appendix, please ensure that it uses the same, two-column NAACL template as it will now be part of the main paper, rather than submitted separately (see [Appendix](#whats-the-deal-with-including-an-appendix-do-i-include-it-as-supplemental) section below for more details).

#  How long can it be?

   For both long and short papers, most *ACL conferences allow one extra page to help
   address reviewer comments.  So long papers are permitted at most 9
   pages of text plus additional pages containing References, and Appendix.
   Short papers get 5 pages of text. Acknowledgements are included in the 9
   (long)/5 (short) pages of content.

   If you are unsure about the page limit for the conference, please contact your conference publication chairs.

# What's the deal with including an Appendix? Do I include it as supplemental?

   You can include an Appendix, but the paper writing must be self-contained before
   the Acknowledgements. The Appendix should appear in main document, after the references.
   The Appendix does not count towards the paper page limit. There is no explicit page limit on the size of the Appendix,
   but please be mindful of what you choose to include. The *ACL style template gives guidance on what is appropriate for
   the Appendix (which is added after the references) vs. Supplementary Material (which are uploaded separately from the paper).

   From the NAACL 2019 style template:
   "Appendices are material that can be read, and include lemmas, formulas, proofs and tables that are not critical
   to the reading and understanding of the paper. Appendices should be uploaded as supplementary material when
   submitting the paper for review. Upon acceptance, the appendices come after the references."

   "Submissions may include non-readable supplementary material used in the work and described in the paper.
   Any accompanying software and/or data should include licenses and documentation of research review as appropriate.
   Supplementary material may report preprocessing decisions, model parameters, and other details necessary for the
   replication of the experiments reported in the paper. Seemingly small preprocessing decisions can sometimes
   make a large difference in performance, so it is crucial to record such decisions to precisely characterize
   state-of-the-art methods. Nonetheless, supplementary material should be supplementary (rather than central)
   to the paper. Supplementary material may include explanations or details of proofs or derivations that do
   not fit into the paper, lists of features or feature templates, sample inputs and outputs for a system,
   pseudo-code or source code, and data. (Source code and data should be separate uploads, rather than part of the paper)."

#  What is the format for the camera-ready copy?

   The file must be in Portable Document Format (PDF) on A4
   paper (210 × 297 millimeters).  We strongly recommend the use of ACL
   LaTeX style files (or Microsoft Word Style files) tailored for this
   year's conference. You can view the style files and detailed
   formatting instructions on your conference website.

   If you are using LaTeX, please create the PDF file with
   <code>pdflatex</code> or <code>xelatex</code>.  This ensures use of
   the proper fonts and also takes advantage of other PDF
   features. You will have the best results using a modern LaTeX
   distribution, in particular,
   [TeX Live](http://www.tug.org/texlive/).

#  How do I ensure that my file is correctly formatted?

   - [Make sure the paper is A4](#format-size)
   - [Embed custom fonts](#format-fonts)

   <a name="format-size"></a>
   -  **Checking the paper size**. Your paper needs to be formatted to
      A4. Here are a
      couple of ways to check this:
      <ul>
      <li>    
      Using pdfinfo. The `pdfinfo` command should include

            Page size:      595.276 x 841.89 pts

        in its output.
      </li>
      <li>
      Using Apple's Preview.app. Open the PDF, and type &#8984-I. It should report the
        correct page size.

      </li>
      <li>
      Using Adobe Acrobat. Open the PDF, navigate to File, Properties..., Description. The
        field labeled "Page Size" should read 8.27 × 11.69 inches in.

      </li>
      </ul>

   <a name="format-fonts"></a>
   - **Embedding Fonts**. You can check your final PDF with the command `pdffonts mypaper.pdf` and confirm that all the fonts say "yes" under "emb". START will not let you upload your final PDF otherwise. If you are including graphics with the PDF extension, these files must also have embedded fonts. If your paper uses Asian fonts, they must be embedded in the PDF file so that they can be displayed by non-Asian versions of the PDF reader (Asian versions ship with a larger set of default fonts.) 
   
   - **Legacy: Margin Checks**. Authors are no longer asked to manually check or correct their margins when uploading their camera-ready papers. 
   


#  What if my paper includes graphics?

   Remember that you are providing a camera-ready copy.  Thus, artwork
   and photos should be included directly in the paper in their final
   positions.  Ideally, you should use vector graphic formats (PDF,
   EPS), which allow the graphics to scale arbitrarily. Avoid GIF or
   JPEG images that are low resolution or highly compressed.

   Your paper must look good both when printed (210 × 297 millimeters size,
   black-and-white) and when viewed onscreen as PDF (zoomable to any
   size, color okay).  Thus, you may want to use color high-resolution
   graphics, allowing onscreen readers to zoom in on a graph and study
   it.  However, *please* check that the same graph or photograph
   is legible when printed on a black-and-white printer.  For example,
   different lines in a graph should not be distinguished only by
   color, although they can <i>also</i> be distinguished by color.

   A good test is to print the paper on your own black-and-white laser
   printer, and to view it in a PDF viewer at different
   resolutions.

   Don't go overboard on resolution; keep file sizes manageable.  Note
   that vector graphics (e.g., encapsulated PostScript) look good at
   any scale and take up little space (unless you are plotting many
   thousands of data points).

#  What about copyright?

   When you submit the paper, you will be asked to sign electronically
   (via the START Conference Manager) or physically the
   [ACL Copyright Transfer Agreement](assets/copyright/copyright.pdf)
   on behalf of all authors. Authors retain many rights under this
   agreement and it is appropriate in the vast majority of cases.
   Please [contact the chairs](mailto:naacl-pub-chairs@googlegroups.com) with
   any concerns regarding copyright.

   Before signing this form, please confirm with your co-authors (and,
   if applicable, your and their employers) that they authorize you to
   sign on their behalf. Please sign your full name (not just your first or last initials).

   NAACL 2019 has its own new [NAACL 2019 Copyright Transfer Agreement](assets/copyright/naacl2019-copyright.pdf).

#  What if my paper's title or author list has changed?

   Then please edit those metadata fields when you upload the
   camera-ready version, so that they will appear correctly in the
   table of contents, author index, conference schedule, etc. <font
   color="red">Please also note that your name will appear in
   conference metadata as you have configured it in Softconf's system</font>,
   so make sure that it is correct there (e.g., capitalization, full
   name, etc). You can change this on
   [user settings page](https://www.softconf.com/naacl2015/papers/user/scmd.cgi?scmd=updateProfile).

   Note: Your conference may or may not allow authors to be added or reordered after submission. Please check with your conference.


#  My question isn't answered here...?

   Please email the current publications chairs for any questions or clarifications. We will update this page if new issues arise.
