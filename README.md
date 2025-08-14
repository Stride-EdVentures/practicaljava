# practicaljava
A book on Practical Java programming

## Front Matter
```
layout: default          # Use the default page template
layout: home            # Use home page template (for index.md)
layout: post            # Use blog post template

title: My Page Title
title: "Chapter 1: Introduction"    # Use quotes if it contains colons or special chars

nav_order: 1            # First in navigation
nav_order: 2            # Second in navigation
# No nav_order = page hidden from navigation

parent: Chapters        # Must match parent page's title exactly
parent: "Chapter 1: Introduction"    # Use quotes for titles with colons

parent: "Chapter 1: Introduction"
grand_parent: Chapters

has_children: true      # This page will have child pages under it
has_children: false     # Default - this page has no children

permalink: /chapters/introduction/     # Custom clean URL
permalink: /about/                     # Instead of /about.html
```

Example for: `chapters/01-intro/overview.md`:
```
---
layout: default
title: Overview
nav_order: 1
parent: "Chapter 1: Introduction"
grand_parent: Chapters
permalink: /chapters/01-introduction/overview/
description: "Overview of key concepts in Chapter 1"
---
```
