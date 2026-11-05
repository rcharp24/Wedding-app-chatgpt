# Wedding HQ — prototype

A browser-based wedding planning prototype.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Internet access is required for the map library, map tiles, address search, and routing services.

## Included
- Responsive dashboard and navigation
- Interactive OpenStreetMap map
- Custom categories with colors and icons
- Add/edit saved pins and search addresses
- Arbitrary two-pin driving routes, distance, ETA, and route steps (OSRM demo service)
- Budget and expense tracking
- Venue shortlist
- Vendor list
- Guest list and RSVP tracking
- Planning checklist
- Manual wedding email log

## Important prototype limitations
- Data is stored in the current browser using localStorage; it is not synchronized between devices or partners.
- The Wedding Inbox does not connect to Gmail or Outlook. Real email integration requires OAuth, provider APIs, a secure backend, and explicit account authorization.
- The public Nominatim and OSRM demo services are suitable for testing only and may be rate-limited. For production, configure a commercial or self-hosted geocoding/routing provider and follow its usage policies.
- This is an MVP prototype, not a production-ready application. Authentication, cloud database, shared permissions, document uploads, calendar sync, seating chart, wedding website, and security hardening remain future development work.
