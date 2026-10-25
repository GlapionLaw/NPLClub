# NPLClub

Static marketing site for **Crosscourt Padel Collective**, a club-neutral padel team organization for NY/NJ/CT and Boston. "Crosscourt" is a working name.

Plain HTML/CSS with a little vanilla JS and no build step. It deploys as-is to GitHub Pages or Netlify.

## Preview

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Before launch

- **Name:** the brand name appears as plain text. To rename, run `grep -rl Crosscourt . | xargs sed -i 's/Crosscourt/NewName/g'`, then replace `assets/img/logo.svg`.
- **Contact form:** `contact.html` posts to `#`. Replace `action="#"` (marked `FORM_ENDPOINT`) with a Tally, Formspree or Google Forms URL.
- **Placeholders:** prices, team names, coaches, partner logos and event dates are provisional.
