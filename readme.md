# Search Engine Optimization (SEO)
A helpful checklist / collection of Search Engine Optimization (SEO) tips and technics.

## Table of Contents
* [URL](#url)
* [Meta Information](#meta-information)
* [Keywords](#keywords)
* [Content](#content)
* [Images](#images)
* [Links](#links)
* [Social Media](#social-media)
* [Sitemap](#sitemap)
* [Errors and access](#errors-and-access)
* [Performance](#performance)
* [UX](#ux)
* [Mobile](#mobile)
* [Validation and accessibility](#Vvlidation-and-accessibility)
* [Search](#search)
* [Analytics](#analytics)
* [Tools](#tools)

### URL
* Descriptive URLs: use a descriptive page url, which should reflect your targeted keyword
* Subdomain or subfolder: subdomains are seen as separate domains
* Hyphans: split words using hyphans
* www or no-www: provide both domains, but set a prefered version in Google Webmaster Tools
* Localisation: chookse a country-specific domain, for better local search results
* [HTTPS](http://googlewebmastercentral.blogspot.be/2014/08/https-as-ranking-signal.html): Security is a top priority for Google

### Meta Information
* Title: each page shound have a unique speaking title (60 - 100 characters) `<title>Website Title</title>`
* Description: each page should have a unique description (max. 160 characters) `<meta name="description" content="">`

### Keywords
* Single: every page shound have a single unique targeted keyword
* Research: rank for keywords with high traffic and less competition
* URL: keyword should appear in URL name
* Title: keyword should appear in page title
* Heading: keyword should appear in headings
* Content: keyword should apear in ~3% of article length
* [Meta Tag](https://www.youtube.com/watch?v=jK7IPbnmvVU): you can ommit the `<meta name="keywords" content="">`, search engines do not use this meta tag

### Content
* Content: Content matters the most in SEO
* Headings: Clear structure `H1` -` H6` max. 70 characters long
* Strong: use `strong` tag to highlight your targeted keyword
* Unique: do not provide duplicated content, use unique content types
* Length: article should be at least 300 words
* Freshness: new content is important. Updating pages or regulary posting is recommended

### Images
* File name: use a short descriptive name
* Alt tag: add an alt-tag this a description of the image (60 - 70 characters)
* Dimentions: add the `width=""` and `height=""` attributes to the image
* [Responsive Images](http://www.w3.org/TR/html-picture-element/): serve the most optimized image corresponding to the window size
* Size: keep the filesize as low as possible
* [Optimization](https://imageoptim.com/): Optimize images by removing some meta information

### Links
* add meaningful title
* Only add external links if you got a backlink to your site
* add `rel="nofollow"` attribute to external links
* add ~ 3 internal links to your content

### Social Media
* Social link rank up your site
* use social snippets [OpenGraph](http://ogp.me/), [Facebook](https://developers.facebook.com/docs/sharing/best-practices), [Twitter](https://dev.twitter.com/cards/getting-started)
* Authorship information

  `<link rel="author" href="https://plus.google.com/u/0/[GOOGLE+ ID]">`

  `<a href="https://plus.google.com/u/0/[GOOGLE+ ID]?rel=author">Google</a>`
* [social profiles](https://developers.google.com/webmasters/structured-data/customize/social-profiles)

  ```
  <span itemscope itemtype="http://schema.org/Organization">
    <link itemprop="url" href="http://www.your-company-site.com">
    <a itemprop="sameAs" href="http://www.facebook.com/your-company">Facebook</a>
    <a itemprop="sameAs" href="http://www.twitter.com/YourCompany">Twitter</a>
  </span>
  ```

### Sitemap
* HTML sitemap: An HTML sitemap allows site visitors to easily navigate a website.
* [XML sitemap](https://support.google.com/webmasters/answer/183668): Help search engines to index your pages
* [Image sitemap](https://support.google.com/webmasters/answer/178636): Increase that your images can be found in Image Search results
* [Video sitemap](https://support.google.com/webmasters/answer/80471): Make sure, search engines know about all the video content on your site
* [Mobile sitemap](https://support.google.com/webmasters/answer/6082207): For feature phones, you can create a mobile sitemap

### Errors and access
* provide 403 - Acced denied page
* provide 404 - Page not found page
* add a `robots.txt` file
* Avoid `FILE_NOT_FOUND` errors

### Performance
* Performance and loading time matters
* only serve concatenated and minified files
* if possible no redirects
* compress images ([ImageOptim](https://imageoptim.com/))

### UX
* User friendly site
* clickable links should not be too small

### Mobile
* add viewport tag

```
 <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1.0">
 ```

* create a mobile-friendly site ([shown in search results](http://googlewebmastercentral.blogspot.be/2014/11/helping-users-find-mobile-friendly-pages.html))
* [Mobile-Friendly Test](https://www.google.com/webmasters/tools/mobile-friendly/)
* [AppLinks](http://applinks.org/documentation/)

### Validation and accessibility
* Write valid markup ([HTML Validator](http://validator.w3.org/) [CSS Validator](http://jigsaw.w3.org/css-validator/))
* use [WAI-Aria](http://www.w3.org/TR/wai-aria/) tags
* use [RichSnippets](http://schema.org/)

### Search
* [Provide a custom search](https://developers.google.com/custom-search/) ([schema.org/SearchAction](http://schema.org/SearchAction), [RichSnippet](https://developers.google.com/webmasters/richsnippets/sitelinkssearch?utm_source=wmc-blog&utm_medium=direct-referral&utm_campaign=sitelinks-searchbox))

### Analytics
* [Google Analytics](http://www.google.com/analytics/)
* [Piwik](http://piwik.org/)
* [Yahoo Web Analytics]( (web.analytics.yahoo.com))

### Tools
* [Google Webmasters](https://www.google.com/webmasters/)
* [Bing Webmasters](http://www.bing.com/toolbox/webmaster)
* [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
* [AdWords Keyword Tool](https://adwords.google.com/KeywordPlanner)
* [Google Trends](http://www.google.com/trends/)
* [Structured Data Testing Tool](http://www.google.com/webmasters/tools/richsnippets)
* [Structured Data Testing Tool](https://developers.google.com/structured-data/testing-tool/)
* [Google+ Snippet Creator](https://developers.google.com/+/web/snippet/)
* [seo tool by feedthebot](http://www.feedthebot.com/tools/)
* [Twitter card validator](https://cards-dev.twitter.com/validator)
* [Facebook Debugger](https://developers.facebook.com/tools/debug)
