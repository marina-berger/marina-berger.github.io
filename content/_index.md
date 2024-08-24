---
title: 'Home'
date: 2024-08-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    id: home
    content:
      title: «Was ist, darf sein. Was sein darf, verändert sich.»
      text: Werner Bock
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "text-black"
      background:
        color: "white"
  - block: stats
    content:
      items:
        - statistic: "Personal Coaching"
          description: |
            für Privatpersonen &  
            individuelle Lebenssituationen
        - statistic: "Business Coaching"
          description: |
            für Fach- und Führungskräfte & 
            Unternehmer
        - statistic: "Bewegung"
          description: |
            für alle, als körperliche Ergänzung  
            im Coaching-Prozess
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: Angebot
      items:
        - name: Personal Coaching
          icon: star
          description: Für Privatpersonen & individuelle Lebenssituationen
        - name: Business Coaching
          icon: star
          description: Für Fach- und Führungskräfte & Unternehmer
        - name: Bewegung
          icon: star
          description: Für alle, als körperliche Ergänzung im Coaching-Prozess
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: Über mich
          text: |
            **Hey. Ich bin Marina!**<br><br>

            Seit über zehn Jahren unterstütze ich Menschen und Unternehmen als Berater und Coach. Für meine Klientinnen und Klienten bin ich ein waches, feinfühliges und sorgfältiges Gegenüber.  

            Meine Arbeit ist theoretisch fundiert und gleichzeitig konkret und anwendbar. Sie basiert auf dem Verständnis, dass alle Antworten, die du suchst, bereits in dir angelegt sind. Um diesen inneren Schatz zu heben, bedarf es einer Begleitung, die absichtslos, wertfrei, offen und individuell ist. All das biete ich dir als Coach.  

            Meine Erfahrung ist - wenn Menschen wieder lernen, ihre Bedürfnisse achtsam wahrzunehmen, ernst zu nehmen und danach zu handeln, stärkt das die Selbstverantwortung für das eigene Leben.  

            Wenn dies geschieht, wird für mich das Schönste an meiner Arbeit sichtbar. Ich sehe die leuchtenden Augen meiner Klientinnen und Klienten, spüre die Leichtigkeit des Fortschritts und höre begeistert von der neu entdeckten inneren Freiheit und dem inneren Frieden. Diese Momente zeigen mir, wie erfüllend und transformierend der Coaching-Prozess sein kann.
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Kurzprofil
            url: https://hugoblox.com/templates
        - title: Large Community
          text: Join our large community on Discord - ask questions and get live responses
          feature_icon: bolt
          features:
            - "Dedicated support channel"
            - "3,000+ users on Discord"
            - "Share your site and get feedback"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Join Discord
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Hugo Smith"
          role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Build your future-proof website
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
