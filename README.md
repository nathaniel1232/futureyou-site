# Future You website

Static marketing site for the Future You iOS app. Plain HTML and CSS, no build step.

- `/` landing page
- `/privacy` privacy policy
- `/terms` terms of use

Before going live, replace every `CONTACT_EMAIL` with a real address:

```bash
grep -rl CONTACT_EMAIL --include=*.html . | xargs sed -i '' 's/CONTACT_EMAIL/you@example.com/g'
```

Deploy: import this repo on vercel.com. Framework preset "Other", no build command, output directory is the repo root.
