# CP Store Grocery website icons

Copy the icon files and `site.webmanifest` into your website's public root (`public/` in Next.js).

Place the following inside the `<head>` of a regular HTML website:

```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="manifest" href="/site.webmanifest">
<meta name="theme-color" content="#425F3B">
<meta property="og:type" content="website">
<meta property="og:image" content="https://YOUR-DOMAIN/og-image.jpg">
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:image" content="https://YOUR-DOMAIN/og-image.jpg">
```

Replace `YOUR-DOMAIN` with your actual domain. Add your page-specific title, description, canonical URL and Open Graph URL independently. Icons support branding in browsers and on devices; favicons alone do not improve search rankings.

For Next.js App Router, files in `public/` are served from `/`; configure icon and manifest paths through the `metadata` export, and `openGraph.images` for `og-image.jpg`.
