# Omar Abdelsalam — Portfolio Website

A single-file, bilingual (English / Arabic) portfolio. No build step, no backend, no paid dependencies. The only external request is the free Google Fonts stylesheet; the site falls back to system fonts if it is blocked.

## Publish on GitHub Pages

1. Sign in to GitHub or create an account.
2. Create a public repository named `omar-abdelsalam-portfolio`.
3. Upload `index.html` to the root of the repository.
4. Open repository **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/(root)`, then save.
7. Wait for GitHub Pages to publish the website.
8. The expected URL format is `https://YOUR-GITHUB-USERNAME.github.io/omar-abdelsalam-portfolio/`.
9. Test the site on a mobile phone in both Arabic and English.
10. Verify the CV and Content Creator Portfolio sharing permissions.

## Things to verify yourself

- [ ] Google Drive CV link opens in a private/incognito window (sharing set to "Anyone with the link").
- [ ] Google Drive Content Creator Portfolio folder opens in a private/incognito window with the same permission.
- [ ] Behance, Vimeo, YouTube, and TikTok links open the right profiles.
- [ ] WhatsApp opens a chat with +20 150 599 3145, and the email link opens your mail app.
- [ ] Dates and job titles in the Experience section match your CV (DONZZY is shown as Social Media Manager, part-time; El DAWLIA's last ~2 years are described as marketing management).
- [ ] Read the Arabic text once as a native reader and adjust any phrasing you'd say differently.
- [ ] Check the site on a real phone in both languages.

## Editing

- All text lives in the `I18N` object near the bottom of `index.html` (`en` and `ar`). Edit both when you change a sentence.
- Colours are CSS variables at the top of the `<style>` block (`--y` is the yellow accent).
- Open the Arabic version directly with `?lang=ar` at the end of the URL.
- Add a social-preview image later by adding an `og:image` meta tag once the site URL is final.
