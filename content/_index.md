---
# Leave the homepage title empty to use the site title
title: Yue Teng
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: markdown
    id: goals
    content:
      title: Goals
      text: <br>1. To gain a practical understanding of how research can inform decision-making and policy development beyond academia, and to develop my skills in non-academic writing, including the ability to write effective policy briefs.<br><br>2. To enhance my understanding of diverse research methodologies and engage in interdisciplinary studies.<br><br>3. To improve my expertise in data analysis, data visualization, and proficiency in writing code using statistical software such as R.
      filters:
        folders:
          - goals
    design:
      columns: "2"
  - block: portfolio
    id: cand3
    content:
      title: CAnD3
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 1
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: "*"
        - name: IDEA
          tag: idea
        - name: GBA+
          tag: gba
        - name: Dragon's Den
          tag: dragonsden
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: "1"
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ""
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: "1"
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: "2"
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: "2"
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: "2"
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: "2"
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        You can contact me here.
      # Contact (add or remove contact options as necessary)
      email: yteng43@uwo.ca
      # phone: 888 888 88 88
      # appointment_url: "https://calendly.com"
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: "94305"
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - "Monday 10:00 to 13:00"
      #   - "Wednesday 09:00 to 10:00"
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: "https://twitter.com/Twitter"
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: "skype:echo123?call"
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: "https://zoom.com"
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: "2"
---
