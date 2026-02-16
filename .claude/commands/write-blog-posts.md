# Write New Blog Posts for Tonal Chaos Trailers

You are writing new SEO-optimized blog posts for tonalchaostrailers.com — a premium trailer music and sound design library targeting music supervisors, studios, producers, ad agencies, creative directors, and content creators.

## Steps

1. **Read the tracker:** Read `blog/BLOG_TRACKER.md` to see what's already published (DO NOT repeat any topics) and which topics are queued.

2. **Pick 2-4 topics** from the "Queued Topics" list. Choose a mix of categories (Licensing, Production, Industry). If the queue is running low, generate new relevant topics first and add them.

3. **Read an existing post** (e.g., `blog/trailer-music-licensing-guide/index.html`) to match the exact HTML template, design, navigation, and styling.

4. **Read `blog/index.html`** to understand the blog listing page structure so you can add new post cards.

5. **For each new post:**
   - Create `blog/[slug]/index.html` matching the existing template exactly (dark theme, nav, breadcrumb, article, CTA, related posts, footer, SEO meta tags, BlogPosting schema)
   - Write 1,000-1,500 words of expert-level content as Tonal Chaos
   - Include internal links to other blog posts and the SourceAudio catalog
   - Use the date of today for the publish date

6. **Update `blog/index.html`:** Add new post cards to the grid (maintain same card structure).

7. **Update `sitemap.xml`:** Add new post URLs.

8. **Update `blog/BLOG_TRACKER.md`:**
   - Add new posts to the "Published Posts" table
   - Add covered topics to "Topics Covered" list
   - Check off used topics from "Queued Topics"
   - Update "Last Published" date

9. **Commit and push** with a descriptive commit message listing the new posts.

## Important Rules
- NEVER duplicate topics that appear in the "Topics Covered" section
- Every post needs unique title, meta description, OG tags, canonical URL, and BlogPosting JSON-LD
- Match the existing dark theme design exactly (bg-[#030303], accent #2563EB, Cinzel headings, Manrope body)
- Include "Journal" as the active nav link on all blog pages
- Every post must have a CTA section with "Search Catalog" (SourceAudio link) and "Get a Quote" (marcus@tonalchaos.com)
- Cross-link between posts in the "Related Posts" section
