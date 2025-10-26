---
# Front Matter: Tells Hugo this is a landing page
title: "Video Insights"
linktitle: "Videos"
url: "/videos/"
summary: "Short-form content on AI, Security Automation, and DevSecOps."
type: landing 

# The widgets that make up the page
sections:
  # Block 1: The Introductory Section (The "Coming Soon" message)
  - block: markdown # Use the simple markdown block
    id: intro # Give it a unique ID
    content:
      title: "Video Insights"
      subtitle: "🚧 Video Content Coming Soon! 🚧"
      text: |
        I am currently engineering my first series of short videos covering topics like **AI in Security Automation, DevSecOps pipelines, and cloud hardening**.
        
        Check back soon!
        
        {{< figure src="/coming-soon.png" alt="Under Construction Clipart" width="400" >}}
    design:
      # Optional: Make the design uniform (similar to the default Bio/Home page)
      columns: '1'
      spacing:
        padding_top: '1rem'
        padding_bottom: '1rem'

  # Block 2: Placeholder for the actual video list when ready (Optional but good practice)
  - block: collection
    id: video_list
    content:
      # This title will appear right above the list of future videos
      title: Featured Shorts
      filters:
        # NOTE: You must use the correct content type here when you start adding videos.
        # If your videos are defined in content/videos/, the kind will be 'section'.
        kinds:
          - section 
    design:
      # Use an empty block to match the clean design of other pages
      view: list # or compact
      columns: '1'

---