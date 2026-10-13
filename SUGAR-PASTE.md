# Sugar Scoop — portal paste
2026-09-26. Ethical AI location only. EarnNow was not changed.

The portal can store media and contact fields. It cannot create the funnel page on this token (`funnels` route is not open). `https://ethicalai.me/sugar` is still 301 to `/404-stop`.

## Already live

| Piece | Value |
|---|---|
| Hero | https://assets.cdn.filesafe.space/REDACTED_GHL_LOCATION_ID/media/bccfd05d-f98d-4d70-8165-d39c9fcf2776.jpg |
| Helper | https://assets.cdn.filesafe.space/REDACTED_GHL_LOCATION_ID/media/9aa2c2ac-95f0-4698-b5ae-06945fc2a4be.jpg |
| Kit zip | https://assets.cdn.filesafe.space/REDACTED_GHL_LOCATION_ID/media/cdd2614d-89ed-4160-b8a0-2c615b3e18be.zip |
| hunt_focus | `REDACTED_FIELD_ID` (`contact.hunt_focus`) |
| comms_consent | `REDACTED_FIELD_ID` |
| consent_source | `REDACTED_FIELD_ID` |
| consent_text | `REDACTED_FIELD_ID` |
| primary_ai | `REDACTED_FIELD_ID` — other offer's picklist. Do not overwrite it. |

Paste files: `sugar.portal.html` and `sugar-in.portal.html`. Image addresses are already swapped. Copy is the file you redid.

## Your clicks

1. New funnel named **SUGAR**. Leave EarnNow and Force Multiplier alone.
2. Step name `sugar`, path `sugar`, published. Paste `sugar.portal.html` into a full-width code element.
3. Step name `sugar-in`, path `sugar-in`. Paste `sugar-in.portal.html`. Robots noindex.
4. Replace the HTML form in `#insider` with a native form. Consent required, not pre-checked.
   - Name, email, mobile — required
   - What you want found → `contact.hunt_focus` — required
   - AI you open most → do not bind this to `contact.primary_ai` until that picklist has this page's choices. Adding choices is safe. Removing the ones already there is not.
   - Consent → `contact.comms_consent` = `yes`, required
5. On submit: tags `sugar-scoop` `warm-lead` `insider-track` `comms-consent`. Set `consent_source` to `ethicalai.me/sugar`. Set `consent_text` to the checkbox paragraph. Redirect to `/sugar-in`.
6. Workflow, form submitted: email `kit-email.html` immediately. Subject: `Your free Sugar Scoop kit — Insider Track`. Optional text: `The kit is in your email. Ethical AI Insider Track. STOP to quit.` No paid step.
7. Attach this funnel to ethicalai.me. Prove GET `https://ethicalai.me/sugar` is 200.
