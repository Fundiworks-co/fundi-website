# Fundi Works website

The public site for Fundi Works. Plain HTML and CSS, no build step, hosted on Netlify.

- `index.html`: the one-page site
- `styles.css`: styles, using the same colours and fonts as `fundi-starter` (`blocks/ui/tokens.css`)
- `fonts/`: Geologica and DM Mono, self-hosted (SIL Open Font Licence, see the OFL files)
- `thanks.html`: shown after the contact form is sent
- `404.html`: page-not-found
- `netlify.toml`: publish settings and security headers

## Contact form

The form uses Netlify Forms (`data-netlify="true"`). Submissions appear in the Netlify dashboard under Forms; set up an email notification there so new messages reach both of us.

## Before launch

Search the files for `DRAFT` and resolve each one:

- [ ] Remove the `noindex` line in `index.html`
- [ ] Both bios confirmed by their owners
- [ ] Contact email on our domain (and WhatsApp number, if wanted)
- [ ] Legal entity line in the footer, once agreed
- [ ] Connect the domain in Netlify and turn on HTTPS

## Preview locally

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080. The contact form only works once deployed to Netlify.

## Changes

Same rules as our other repos (`fundi-starter/CONTRIBUTING.md`): a branch per change and a pull request the other person approves.
