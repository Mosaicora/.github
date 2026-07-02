# Mosaicora

<p align="center">
  <strong>Automatic Open Graph images for every page.</strong>
</p>

<p align="center">
  <a href="https://mosaicora.io">Website</a> ·
  <a href="https://dash.mosaicora.io/register">Start for free</a> ·
  <a href="https://mosaicora.io/templates">Templates</a> ·
  <a href="https://mosaicora.io/integrations">Integrations</a> ·
  <a href="https://mosaicora.io/tools/open-graph-checker">Open Graph Checker</a>
</p>

---

## What is Mosaicora?

Mosaicora helps websites generate branded, page-specific Open Graph images automatically.

Instead of using the same fallback image for every shared URL, Mosaicora turns each page’s title, description, image, category, product data, or other metadata into a social preview image that is ready for platforms like Facebook, X, LinkedIn, WhatsApp, Slack, and Microsoft Teams.

Use Mosaicora to make every shared link look intentional, readable, and on brand.

---

## Why it exists

Most websites have one of these problems:

- every page shares the same generic preview image;
- social cards show cropped, outdated, or low-context images;
- blog posts, product pages, docs, and landing pages need custom previews but designing them manually does not scale;
- teams want better social previews without adding a design step to every publishing workflow.

Mosaicora solves this with reusable templates, hosted image URLs, and automatic generation based on page context.

---

## Core capabilities

- **Dynamic OG images per URL**  
  Generate a unique social preview image for each page.

- **Reusable brand templates**  
  Keep colors, typography, layout, logos, and visual style consistent across your site.

- **Hosted `og:image` URLs**  
  Reference Mosaicora-generated images directly from your page metadata.

- **Automatic page content extraction**  
  Use existing page metadata and content as the source for generated images.

- **Refresh-aware workflow**  
  Regenerate previews when page content changes.

- **Developer-friendly integration**  
  Connect through standard Open Graph tags, framework metadata, scripts, or API-based workflows.

---

## Example metadata

```html
<meta property="og:image" content="https://cdn.mosaicora.io/s/[site-id]/[page-path].jpg" />
<meta property="og:title" content="Your Page Title" />
<meta property="og:description" content="A clear description of your page" />
