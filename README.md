# Panos Vorgias — website files

Replacement HTML, CSS, and a photo for the supplied GitHub Pages website.
It uses plain HTML and CSS; no installation or build command is required.
It links to the PDFs already in your repository.

## Upload to GitHub

1. Extract the ZIP on your computer.
2. Open your existing website repository on GitHub.
3. Upload the extracted contents into the repository's root, replacing
   `index.html`, `research.html`, and `style.css`. Do not upload the ZIP itself
   or add an extra enclosing folder.
4. Upload the included photo to `assets/images/job_market_photo_panos.jpeg`.
   Keep your existing CV and JMP PDFs at the paths below.
5. Commit the changes using your repository's existing publishing setup.

Files included in this ZIP:

```text
index.html
research.html
style.css
assets/images/job_market_photo_panos.jpeg
```

Existing document paths used by the pages:

```text
assets/docs/jmp.pdf
assets/docs/cv.pdf
```

PDFs are not included in this ZIP. Keep the current versions in your repository.
If a document uses a different path there, update its `href` in the HTML to match.
The old `assets/images/photo.jpeg` file can remain in the repository; the new
homepage loads `job_market_photo_panos.jpeg`.

## What changed

- Centered navigation, name, affiliation, and a larger portrait.
- A cream background and restrained gold accents, with serif body text.
- The homepage uses the ownership-tradeoff wording discussed in this thread,
  including the brief reference to differences in firms' research capabilities.
- Direct links to the JMP and CV appear on the homepage.
- Research abstracts use built-in, keyboard-accessible expand/collapse controls;
  the JMP abstract is expanded initially.
- The JMP PDF link now points to `assets/docs/jmp.pdf`. The two work-in-progress
  entries retain their abstracts without the old PDF links to the homepage.
- The layout adjusts for phones and works without JavaScript or external fonts.

## Later edits

- Homepage text: `index.html`.
- Paper titles, abstracts, and coauthors: `research.html`.
- Colors, type sizes, and spacing: the variables and rules in `style.css`.
- Updated documents: replace `assets/docs/jmp.pdf` or `assets/docs/cv.pdf`,
  keeping the filenames the same.

For a white background, change `--background` in `style.css` to `#ffffff` and
the two HTML `theme-color` values to match.
