---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  # - block: features
  #   content:
  #     title: Skills
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: chart-line
  #         icon_pack: fas
  # - block: experience
  #   content:
  #     title: Experience
  #     # Date format for experience
  #     #   Refer to https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: CEO
  #         company: GenCoin
  #         company_url: ''
  #         company_logo: org-gc
  #         location: California
  #         date_start: '2021-01-01'
  #         date_end: ''
  #         description: |2-
  #             Responsibilities include:

  #             * Analysing
  #             * Modelling
  #             * Deploying
  #       - title: Professor of Semiconductor Physics
  #         company: University X
  #         company_url: ''
  #         company_logo: org-x
  #         location: California
  #         date_start: '2016-01-01'
  #         date_end: '2020-12-31'
  #         description: Taught electronic engineering and researched semiconductor physics.
  #   design:
  #     columns: '2'

  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      columns: '2'
      view: community/my
  # - block: collection
  #   id: pubs
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
  #     columns: '2'
  #     view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact

  - block: accomplishments
    id: honor
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Selected Honors & Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url:
          date_end: ''
          date_start: '2023-06-01'
          description: 'The project proposal submitted under the Horizon Europe Marie Skłodowska- 
          Curie Actions call MSCA Postdoctoral Fellowships 2022 by Mengyue Xu following evaluation by 
          an international panel of independent experts was recognised as a high-quality project 
          proposal.'
          organization: European Commission Horizon 
          organization_url: 
          title: Seal of Excellent for Europe Marie Skłodowska-Curie Actions Postdoctoral Fellowships proposal 2022
          url: 

        - certificate_url:
          date_end: ''
          date_start: '2021-06-08'
          description: 'Mengyue Xu was nominated by Prof. Xinlun Cai for her exceptional contributions to Thin-film Lithium Niobate Electro-optic devices for Coherent Optical Communication.'
          organization: Photonics Society of Chinese Heritage (PSC)
          organization_url: https://psc-sc.org/about-psc/
          title: Tingye Li Memorial Scholarship
          url: 'https://psc-sc.org/tingye-li-memorial-scholarship-announcement-and-winners/'

        - certificate_url: 
          date_end: ''
          date_start: '2023-04-20'
          description: '"Dual-polarization Thin-film Lithium Niobate IQ modulator for Terabit-per-second Transmission" was selected as China’s Top Ten Advances in Optics.'
          organization: Chinese Laser Press
          organization_url:
          title: China’s Top Ten Advances in Optics 2022 中国光学十大进展
          url: 'https://www.opticsjournal.net/CL/ZGGX?type=view&postid=PT230420000003jGmJp'

        - certificate_url: 
          date_end: ''
          date_start: '2020-03-20'
          description: '"High-performance coherent optical modulators based on thin-film lithium niobate platform" was selected as China’s Top Ten Advances in Optics.'
          organization: Chinese Laser Press
          organization_url:
          title: China’s Top Ten Advances in Optics 2020 中国光学十大进展
          url: 'https://news.sciencenet.cn/htmlnews/2021/4/456647.shtm'

        - certificate_url: 
          date_end: ''
          date_start: '2019-03-20'
          description: '"High-performance hybrid silicon and lithium niobate Mach–Zehnder modulators for 100 Gbit s−1 and beyond" was selected as China’s Top Ten Advances in Optics.'
          organization: Chinese Laser Press
          organization_url:
          title: China’s Top Ten Advances in Optics 2019 中国光学十大进展
          url: 'https://news.sciencenet.cn/htmlnews/2020/3/437223.shtm'

        - certificate_url: 
          date_end: ''
          date_start: '2022-09-01'
          description: 'Mengyue won the fourth place in Light Doctoral Academic League (Final) and the first place in Light Doctoral Academic League (Semi-final).'
          organization: Light Publishing Group
          organization_url:
          title: Annual Third Prize, Light Doctoral Academic League (Final)
          url: 'https://www.lightpublishing.cn/conference2022?lang=en'
    design:
      columns: '2'

  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: xu1733@purdue.edu
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: 610 Purdue Mall
        city: West Lafayette
        region: IN
        postcode: '47906'
        country: United States
        country_code: US
  #     directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'
---
