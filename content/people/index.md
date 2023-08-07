---
date: "2022-10-24"
image:
  placement: 1
  caption: ""
  focal_point: "Center"
  preview_only: false
  alt_text: 
  filename: coders.jpg
sections:
- block: markdown
  content:
    title: 👥 Meet Our Team
    subtitle: 🤝 [Our collaborators can be found here](https://jaspershen-lab.github.io/collaborators/)
    text: |-
      I'd be happy to help you with your query! However, "our team" is a bit vague. Could you please provide more context or specify what kind of information you're looking for regarding "our team"? Are you looking for tips on building a team, managing a team, or something else entirely? The more details you provide, the better I can assist you.
      {{% callout note %}}
      [Our collaborators can be found here](../collaborators/).
      {{% /callout %}}
  design:
    columns: '1'
    background:
      image: 
        filename: team.jpg
      filters:
        brightness: 0
      #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
      size: cover
      # Image focal point. Options include `left`, `center` (default), or `right`.
      position: center
      # Use a fun parallax-like fixed background effect on desktop? true/false
      parallax: true
      # Text color (true=light, false=dark, or remove for the dynamic theme color).
      text_color_light: true

- block: about.biography
  content:
    title: Principal Investigator `:man_teacher:`
    username: admin

- block: people
  content:
    sort_ascending: true
    sort_by: Params.last_name
    title: 👥 Other members
    user_groups:
    - Researchers
    - Grad Students
    - Administration
    - Visitors
    - Alumni
  design:
    show_interests: true
    show_role: true
    show_social: true
    show_organizations: true
    
- block: markdown
  content:
    title: Alumni Summary
    text: |-
      <iframe width='100%' height='700' src="https://docs.google.com/spreadsheets/d/1SdmT8HUF7bNdddzfAxXsrrzuBBv8nMmyn15Hm-3d650/edit?usp=sharing"></iframe>
  design:
    columns: '1'
    
- block: markdown
  content:
    title:
    subtitle: ''
    text:
  design:
    columns: '1'
    background:
      image: 
        filename: team.jpg
        filters:
          brightness: 1
        parallax: false
        position: center
        size: cover
        text_color_light: true
    spacing:
      padding: ['20px', '0', '20px', '0']
    css_class: fullscreen
    
title: People
type: landing
---
