---
title:
type: landing

sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: 
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: ilya-pavlov-OqtafYT5kTw-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: hero
    content:
      title: Hugo Blox
      text: Build your site with blocks 🧱
      primary_action:
        text: Get Started
        url: https://example.com
        icon: sparkles
      secondary_action:
        text: Read the docs
        url: https://example.com
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
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: 'Check out my recent blog posts below!'
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: card
---