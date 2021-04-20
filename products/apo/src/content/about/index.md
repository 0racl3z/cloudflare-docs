---
title: About
order: 0
---

# Automatic Platform Optimization

With Automatic Platform Optimization (APO), Cloudflare serves your entire site from our edge network, ensuring improved performance for customers visiting your site. Typically, Cloudflare only caches static content, but with APO, you can cache dynamic content — like HTML — to serve the entire site from the cache. Serving from the cache removes round trips from the origin to drastically improve TTFB (time to first byte) and other site performance metrics. In addition to caching dynamic content, APO caches third-party scripts to further reduce the need for requests that leave Cloudflare's edge network.

With APO, you can manage your WordPress site as usual. Whenever you update content in WordPress, Cloudflare updates content on our edge via Cloudflare's WordPress plugin to prevent serving stale content. Additionally, for logged-in or admin users, we will bypass the cache ensuring that private content is not cached and served to other visitors.
