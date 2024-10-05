---
title:
type: landing

sections:
  - block: hero
    content:
      title: 박현수의 이력서
      text:
      color: '#000' 
      primary_action:
        text: 요약
        url: summary/
        icon: sparkles
      secondary_action:
        text: 이력서
        url: authors/
        color: '#000'
      announcement:
        text: Announcing the release of version 1.
        link:
          text: Read more
          url: https://example.com
    design:
      background:
        image:
      # Name of image in `assets/media/`.
          filename: jonathan-petersson-a6N685qLsHQ-unsplash.jpg
      # Apply image filters?
          filters:
        # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.3
      #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
      # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
      # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
      # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true
---