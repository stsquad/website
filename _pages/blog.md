---
title: Blog
permalink: /blog/
description: >
    This is the official Linaro blog.
flow:
    - row: container_row
      sections:
        - format: custom_include
          source: blog/post_search.html
          payload:
              name: url
              data: /assets/json/posts.json
              category: Blog
          # category: News
        - format: custom_include
          source: blog/display_latest_posts.html
          # category: News
---