# CruiseReview auto-poster

Generates a helpful cruise article (first-time tips, ship reviews, deal guides)
with Groq and posts it to r/CruiseReview, 5x/day via GitHub Actions. Self-approves
each post (the account mods the sub) so Reddit's affiliate-domain spam filter
doesn't remove it. Tracks used topics in posted.json.

Secrets: REDDIT_CLIENT_ID/SECRET/USERNAME/PASSWORD, GROQ_API_KEY.
