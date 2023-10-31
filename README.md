# ITY-Project01-2021

Solution for the 1st project from the subject _'ITY (Typography and Publishing)'_ for the academic year 2020/21 at VUT FIT. \
Řešení 1. projektu z předmětu _'ITY (Typografie a publikování)'_ pro akademický rok 2020/21 na VUT FIT.

## Task

Create a document in LaTeX that closely resembles the sample document.

### General Information for the Project:

1. **Appearance**:
   - Don't aim to achieve an exact appearance as the sample document.
   - It's better to use correct LaTeX structures with slight variations than to use tricks for a "perfect" replica (e.g., inserting artificial horizontal or vertical spaces).
2. **Document Content**:
   - The document itself has useful information for the proper completion of the project. Hence, read the document text carefully.
3. **Commands Used**:
   - Commands used in document typesetting were mentioned in the ITY lectures, with a few exceptions.
   - Some previously unmentioned commands are highlighted in the document text.
   - However, some commands not discussed before were used; but finding them (integral to practical LaTeX use) shouldn't be challenging.
4. **Special Attention**:
   - Pay attention to using correct commands for listing, sections, and footnotes.
   - Be cautious with the correct typesetting of website addresses, emails, and section links. All links in the document are clickable and highlighted when hovered over.
   - For section links, be wary of the correct translation; incorrect translations can lead to "??", appearing instead of links.

---

### Basic Document Parameters:

1. **Page Size**: A4
2. **Text Area Dimensions**: 18x25cm
3. **Left Margin**: 1.8cm
4. **Top Margin**: 1.8cm
5. **Font**: Standard 10pt
6. **Source Text Encoding (Optional)**: utf8
7. **Font Encoding**: T1
8. **Two-column Layout**: Use the 'twocolumn' parameter of the 'article' document class.

---

### Document Compilation Information:

The sample document was typeset in LaTeX using the following tools:

1. **Tools**:

   - latex
   - dvips -t a4
   - ps2pdf

2. **Note**: When using pdflatex, the resulting file looks identical but is twice the size.

## Evaluation

| Mistake                                                                          | Penalties |    Status |
| :------------------------------------------------------------------------------- | :-------: | --------: |
| Links to sections set 'hard' or in a non-standard way (correct: \label and \ref) |   -0.5    | Corrected |

Total points: **9.5/10**
