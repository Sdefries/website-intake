# SponsorAPurpose — Netlify Intake Form

Hosted at: `intake.sponsorapurpose.org`

## Multi-tenant URLs

Each client gets their own unique URL:

```
intake.sponsorapurpose.org/client/flathead-animal-shelter
intake.sponsorapurpose.org/client/guardian-pet-trust
intake.sponsorapurpose.org/client/nw-montana-humane
```

The client ID is automatically captured from the URL and included in every Netlify form submission so you know which client submitted.

## Deploy to Netlify

1. Push this folder to a GitHub repo
2. Connect repo to Netlify
3. Set publish directory to `.`
4. Add custom domain: `intake.sponsorapurpose.org`

## Slack Notifications

In Netlify dashboard:
- Site Settings → Forms → nonprofit-intake → Form notifications
- Add notification → Slack integration
- Paste your webhook URL
- Every submission pings your channel with all fields

## Viewing Submissions

Netlify dashboard → Forms → nonprofit-intake

All submissions stored there, filterable, downloadable as CSV.

## Creating a new client URL

Just make up a slug and send it:
```
intake.sponsorapurpose.org/client/their-org-name
```

No setup needed — the slug gets captured automatically on submit.
