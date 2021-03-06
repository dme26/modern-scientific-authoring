---
layout: lesson
subtitle: Lesson Design
---
## Stage 0 - Assumptions

*   Audience
    *   Graduate students or equivalent in *all* fields
        *   Numerate disciplines (astronomy, economics)
        *   Digital humanities
        *   Librarians
    *   Who are writing, publishing, and managing papers, theses, grant proposals, lessons, etc.
*   Prerequisites
    *   Git/GitHub (for GitHub Pages)
    *   Command line (for Pandoc)
    *   ...which is a problem, because Data Carpentry doesn't cover either
*   Requirements
    *   Half day: 3.0 hours of instruction + exercises
    *   Learners use their own machines

As stated in the "Manuscripts" section of
"[Good Enough Practices in Scientific Computing][good-enough]",
we want learners to:

1.  Make text accessible to yourself and others now and in the future
2.  Reduce chances of work being lost or people overwriting each other's work.
3.  Make it easy to track and combine contributions from multiple collaborators.
4.  Avoid duplication and manual entry of information,
    particularly in constructing bibliographies, tables of contents, and lists
5.  Make it easy to regenerate the final shared form (e.g., the PDF),
    and to tell if the PDF in hand is up to date.
6.  Make it easy to share the final version with collaborators and submit it to journals

We recommend against traditional desktop tools like LibreOffice and Microsoft Word
because they make collaboration difficult:
six people mailing each other copies of a paper with "Track Changes" enabled
is a sure way to lose work (and time).
The nerd alternative is:

1.  Manuscripts are written in a plain text format such as LaTeX or Markdown that plays nicely with version control
2.  Tools needed to compile manuscripts are managed just like tools used to do simulation or analysis

But as Stephen Turner said:

> ...try to explain the notion of compiling a document to an overworked physician you collaborate with.
> Oh, but before that, you have to explain the difference between plain text and word processing.
> And text editors.
> And Markdown/LaTeX compilers.
> And BiBTeX.
> And Git.
> And GitHub. Etc.
> Meanwhile he/she is getting paged from the OR...
>
> ...as much as we want to convince ourselves otherwise,
> when you have to collaborate with those outside the scientific computing bubble,
> the barrier to collaborating on papers in this framework is simply too high to overcome.
> Good intentions aside,
> it always comes down to "just give me a Word document with tracked changes," or similar.
> There's always a least common denominator who just isn't going to be on board for writing like this.

We therefore *also* support an alternative to text + version control:

1.  Manuscripts are written using Google Docs or some other online tools with rich formatting and change tracking
2.  A short text file is added to the `doc` directory with metadata about each online manuscript
    *   Just as the `data` directory might contain links rather than actual data
3.  The manuscript is downloaded and saved in `doc` in an editable form (e.g., `.docx` or `.odt`) after major changes

The justification is:

*   If the document lives online (Google Docs or Authorea),
    then everyone's changes are in one place,
    and hence don't need to be merged manually.
*   If the document lives in a version control system (GitHub),
    it provides good support for finding and merging differences resulting from concurrent changes.

But we need to go further.
If people adopt open review and comment on each other's work on blogs and via Twitter,
the under-represented (e.g., women and some minorities) may be discouraged from taking part
(as has happened with open source).
Any discussion of how to use the web for scientific publishing *must* include
discussion of how it can be mis-used,
and what we can do about it.
FIXME: translate this into a lesson.

## Stage 1 - Desired Results

### Goals

*   Understand the pros and cons of
    1.  Desktop WYSIWYG (e.g., Microsoft Word)
    2.  Online WYSIWYG (e.g., Google Docs)
    3.  Plain text in version control (e.g., Markdown + GitHub)
*   Have hands-on experience with approach #3 (plain text + version control)
*   Understand the similarities and differences between Markdown and LaTeX
*   Have an ORCID and know what to do with it
*   Understand how and why to publish and cite software and data
*   Understand the pros and cons of new publishing and review models

### Essential Questions

*   How can I manage the flood of information in my field?
*   How can I make my work more accessible to others in my field?
*   How does desktop WYSIWYG + email impede collaboration?
*   Why is plain text + version control so technically demanding?
*   How do publishers and researchers keep track of who published what?
*   How can open access scientific publishing be sustainable?
*   What are the pros and cons of open review?

### Learners Will Be Able To...

*   write Markdown
*   compile Markdown to PDF or HTML using Pandoc
*   publish Markdown using GitHub Pages
*   create a PDF using Authorea
*   comment on a web page using hypothes.is
*   add their ORCID to electronic manuscripts
*   get a DOI for a data set from Figshare or Zenodo
*   review a document on Google Docs
*   review a document on GitHub

### Learners Will Know...

*   what markup is and why it exists
*   that *every* document uses markup - the only question is whether it's displayed or not
*   the advantages of making data and software citable
*   how and why to participate in online discussions of research
*   how LaTeX, Pandoc, and Authorea work
*   how and why to use [hypothes.is](hypothes.is)
*   what ORCID is
*   why data and programs should have DOIs
*   how pull requests work (so that updating and reviewing is understandable)

## Stage 2 - Assessment

FIXME: need a dozen sections like this:

### Topic title

*   Teaching: 5-10 min
*   Exercises: 5-10 min
    *   FIXME: one-line explanation of exercise

## Stage 3 - Learning Plan

FIXME

[good-enough]: https://github.com/swcarpentry/good-enough-practices-in-scientific-computing
