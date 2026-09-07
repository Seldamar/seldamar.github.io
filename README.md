# selinozdamar.github.io

Personal academic website for the 2026–27 economics job market. Plain HTML and CSS, no build step.

## Files

- `index.html` – the whole site (content and styles in one file)
- `assets/Selin_Ozdamar_CV.pdf` – CV linked from the sidebar button
- `assets/photo.jpg` – portrait

## Publish on GitHub Pages

1. Create a GitHub account if you don't have one, then create a **public** repository named exactly `<your-username>.github.io`.
2. From this folder run:

   ```bash
   git init
   git add .
   git commit -m "Job market website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```

3. In the repository on GitHub go to **Settings → Pages**, set Source to *Deploy from a branch*, branch `main`, folder `/ (root)`, and save.
4. After a minute the site is live at `https://<your-username>.github.io`.

## Updating

Edit `index.html`, replace the PDF in `assets/` with a new CV, then:

```bash
git add .
git commit -m "Update CV"
git push
```

## Things to fill in

Search `index.html` for these spots:

- **Job Market Paper**: the first dissertation essay is placed as the JMP. Swap the two `<article>` blocks if the pandemics paper is your JMP instead.
- **References**: only your supervisor is listed. Add committee members or other letter writers to the `.refs` list under Contact.
- **Teaching**: no teaching section yet because the CV has none. Add a section between Presentations and Education when you have TA or lecturing experience to list.
- **Third essay**: add an abstract and a link when a draft is ready.
- **Google Scholar / SSRN author page / LinkedIn**: add links in the sidebar `.contact` block once you have them.
