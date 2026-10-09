# tidemark-site

The website of [Tidemark](https://github.com/burak-kayaa/tidemark), which turns the traces of
a workday into worklogs. Its releases are published here (Releases), from Tidemark's release
workflow; the Download section links the latest version's files, and the app reads
`latest.json` from the latest release to offer new versions.

One static page, `index.html`, with its styles and script inline, like
[canya-site](https://github.com/burak-kayaa/canya-site). Open it in a browser to work on it.

The page looks like the app: the logo's blue to act and its gold for what is logged, on quiet
ground, with Sora for headings and IBM Plex Sans for text (from Google Fonts). The hero is a
picture of the app's review of a sample day, drawn in HTML rather than a screenshot; its strip
of the day's hours fills in when the page loads (not with reduced motion). Below it, each
section is a band of its own: how it works, what it does (with a sample of a sheet being filled
in), privacy, download. The icons (`favicon.*`, `apple-touch-icon.png`, `icon-*.png`,
`site.webmanifest`) come from the Tidemark brand kit; `og-image.png` is the picture a shared
link shows.
