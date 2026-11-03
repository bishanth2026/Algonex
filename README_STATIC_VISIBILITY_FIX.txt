ALGONEX STATIC VISIBILITY FIX

This update addresses the blank/hidden content visible in the previous local preview.
The captured page had inline data-reveal opacity:0 styles intended to be activated by
client-side JavaScript. The static export does not run the original reveal controller,
so those elements remained invisible. The CSS now makes captured sections and the
hero sequence visible without depending on that missing controller.

The original source's missing photographic assets cannot be recovered from the
repository snapshot; this package preserves the available original SVG artwork and
existing content. This is a static visual repair, not a verified full recreation of
the original hosted Next.js application. Test index.html locally and inspect all
sections before publishing.
