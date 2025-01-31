---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: 'I’m Rayel, a Computer Science student at Concordia.0'
    subtitle: >-
      I’m a passionate developer with experience in building dynamic,
      user-friendly websites. With a strong foundation in programming, data
      structures, and web development, I specialize in crafting high-performance
      websites and applications. My goal is to blend creativity with technology
      to develop innovative digital solutions.
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    text: >+
      ### **Education**


      **Concordia University, Montreal**

      *Bachelor of Computer Science* (In Progress)

      Relevant Courses:


      *   Web Programming, Databases, Data Structures & Algorithms, Operating
      Systems, Theoretical Computer Science, Probability & Statistics, Formal
      Methods, Marketing & Management.


      ### **Experience**


      #### **Freelance Web Developer** (2019 – Present)


      *   Designed and developed websites for small businesses, improving online
      visibility.


      *   Created custom logos, social media branding, and digital marketing
      strategies.


      *   Managed hosting, domains, and WordPress, Shopify, and Magento-based
      sites.


      ### **Technical Skills**


      *   **Programming:** Java (OOP), JavaScript, HTML/CSS, SQL, Python


      *   **Web Development:** WordPress, Shopify, Magento, React (learning)


      *   **Database Management:** MySQL, Firebase


      *   **Hosting & Domains:** Website Deployment & Maintenance


      *   **Marketing & Business:** Google Ads, Social Media Marketing, SEO

  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: FeaturedPostsSection
    subtitle: Featured Posts
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-one.md
    colors: colors-f
    variant: variant-c
    elementId: ''
    showDate: true
    showExcerpt: true
    showFeaturedImage: false
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
  - type: CtaSection
    title: "Got an interesting project or opportunity? Tell me more...\U0001F4AC"
    text: ''
    actions:
      - type: Button
        label: Contact me now
        altText: ''
        url: 'mailto:contact@rayels.dev'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: full
<<<<<<< HEAD
    elementId: ''
=======
    title: "Got an interesting project or opportunity? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: Company
          label: Company
          hideLabel: true
          placeholder: Company
          isRequired: true
          width: 1/2
          type: TextFormControl
        - type: TextFormControl
          name: Phone Number
          label: Phone Number
          hideLabel: true
          placeholder: Phone Number
          width: full
          isRequired: false
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
>>>>>>> parent of 2000321 (Publish)
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: col
      title:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
---
