MOMENTUM ENTER THE ARENA — UPDATED WEBSITE

The existing Road to Momentum section has been replaced with ENTER THE ARENA.

Structure:
- index.html — main website
- events-data.js — single editable event data source
- events/<event-slug>/index.html — reusable event detail page structure
- Assets/ — existing website assets plus event-banners/ and organisers/ folders

To update an event, edit only events-data.js. The main cards and detail pages read the same data.

Current source data preserved from the supplied site:
- Event names
- Dates
- Times
- Existing flagship posters

Information not present in the supplied site is marked TO BE ANNOUNCED, including venue, prize and team size. Replace those fields in events-data.js when the official information is available.

Categories are editable classifications used for the requested filter UI.

Registration links currently use the site's existing placeholder URL. Replace registrationLink for each event with its actual registration form URL.
