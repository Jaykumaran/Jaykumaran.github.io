---
# This file is for LISTING your projects.
# It should be located either at the root of your site as 'projects.md'
# OR in the '_pages' folder as 'projects.md' (or any other name, but the permalink matters).

layout: collection       # Use the theme's layout for displaying collections
title: "My Projects"       # The title that will appear on this page
permalink: /projects/      # CRUCIAL: This makes the page accessible at your-site.com/projects/
                           # This MUST match the URL in your navigation.yml
collection: projects     # CRUCIAL: Tells the layout WHICH collection to display.
                           # This MUST match the collection name in _config.yml (and your _projects folder)
entries_layout: grid     # Displays items in a grid/card format (theme-dependent, good for Minimal Mistakes)
# sort_by: date          # Optional: 'date', 'title', or a custom front matter field from your project files
# sort_order: descending # Optional
author_profile: true       # To show your sidebar
---

Explore some of the projects I've worked on. Click any project for more details.

<!--
The `layout: collection` with `entries_layout: grid` (when using a theme like Minimal Mistakes)
will automatically loop through your `_projects` items and display them using the theme's
pre-defined grid/card styling. You usually don't need to write any HTML or Liquid loops here.
-->
