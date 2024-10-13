---
title: 'Home'
date: 2024-10-13
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
        - statistic: ""
          description: ""
        - statistic: "Business Coaching"
          description: |
            für Fach- und Führungskräfte & 
            Unternehmer
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: ""
      items:
        - name: Personal Coaching
          icon: star
          description: |
            In unseren Einzelsitzungen biete ich dir einen vertraulichen Rahmen, um deine Anliegen wie persönliche Weiterentwicklung, Beziehungsfragen, Krisenbewältigung oder die Suche nach mehr Lebensbalance zu klären. Wir konzentrieren uns auf das, was dir wichtig ist – deine Wünsche und Bedürfnisse – und arbeiten mit dem, was du im Hier und Jetzt erlebst und ausdrückst. Gemeinsam beleuchten wir auch unangenehme Aspekte, um herauszufinden, wie sie dich möglicherweise hemmen oder gar blockieren. So gewinnst du ein tieferes Verständnis für deine Situation, entwickelst neue Perspektiven und erweiterst deinen Handlungsspielraum. Ziel ist es, deine Wirksamkeit zu erhöhen und spürbare Fortschritte in deinem Alltag zu erzielen.
        - name: Business Coaching
          icon: star
          description: |
            In einer dynamischen Arbeitswelt ist kontinuierliches Wachstum entscheidend. Mein Business Coaching richtet sich an Fach- und Führungskräfte sowie Unternehmer, die sich beruflich weiterentwickeln und ihr Unternehmen auf das nächste Level bringen möchten.
            Ein wesentlicher Bestandteil meines Coachings ist die Vertiefung der Selbstreflexion und das Bewusstmachen von inneren Mustern. Dies ermöglicht dir, tiefgreifende Veränderungen vorzunehmen und dein Führungsverhalten nachhaltig zu verbessern. Darüber hinaus unterstütze ich dich dabei, deine individuellen Stärken zu fördern und eine authentische Führungsidentität zu entwickeln. Durch gezielte Übungen und Reflexionen hilfst du dir selbst, innere Klarheit zu gewinnen und deine persönlichen sowie beruflichen Ziele effektiver zu erreichen.
            Ich arbeite mit einem systemischen Ansatz, der die Wechselwirkungen und Dynamiken in deinem Unternehmen berücksichtigt. Wir betrachten dein Unternehmen als ein komplexes System, in dem jede Veränderung in einem Bereich Auswirkungen auf andere Bereiche hat.
            Gemeinsam analysieren wir die Teamdynamik und entwickeln gezielte Lösungen, um die Wechselwirkungen positiv zu nutzen und deine spezifischen Ziele zu erreichen.
  - block: cta-image-paragraph
    id: about
    content:
      items:
        - title: Über mich
          text: |
            **Hey. Ich bin Marina!**<br><br>
            
            Seit über zehn Jahren unterstütze ich Menschen und Unternehmen als Berater und Coach.<br><br>
            
            In meiner Arbeit lege ich großen Wert auf Empathie, Genauigkeit und eine fundierte, praxisorientierte Herangehensweise. Ich glaube daran, dass die Antworten auf deine Fragen bereits in dir selbst liegen. Mein Ansatz besteht darin, dir durch eine wertfreie, offene und individuelle Begleitung zu helfen, diesen inneren Schatz zu heben und zu nutzen. Indem du lernst, deine Bedürfnisse achtsam wahrzunehmen und danach zu handeln, stärkst du deine Selbstverantwortung.<br><br>
            
            Wenn das passiert, wird für mich der schönste Teil meiner Arbeit sichtbar: Ich sehe die strahlenden Augen meiner Klientinnen und Klienten und erkenne ihre neu gewonnene innere Freiheit. Diese Momente zeigen mir, wie erfüllend und transformierend der Coaching-Prozess sein kann.<br><br>
          # Upload image to `assets/media/` and reference the filename here
          image: about-me.jpeg
          button:
            text: Kurzprofil
            url: https://hugoblox.com/templates
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-image-paragraph
    id: coaching
    content:
      items:
        - title: Coaching
          text: |
            **Hey. Schön, dass du da bist! Willkommen auf deinem Weg der Selbstentfaltung.**<br><br>
            
            Als Coach ist es meine Aufgabe, Menschen auf ihrem Weg der persönlichen und beruflichen Entwicklung zu begleiten. Ein effektives Coaching setzt voraus, dass ich meine Klientinnen und Klienten ganzheitlich wahrnehme – mit ihrem Wesen, ihren individuellen Erfahrungen, ihren Stärken, ihren nonverbalen Signalen und ihren Herausforderungen. Auf dieser Basis kann ich kritisch hinterfragen, meine Irritationen benennen und gleichzeitig einfühlsam und zugewandt bleiben. Meine Erfahrung zeigt, dass jeder Mensch die notwendigen Antworten auf seine Herausforderungen bereits in sich trägt. Oft braucht es aber den gezielten Dialog und ein unterstützendes Gegenüber, um diese Antworten ans Licht zu bringen.<br><br>
            
            Meine Arbeit basiert auf der Metatheorie der Veränderung des Hephaistos Coaching Zentrums München. Diese theoretische Grundlage ermöglicht es mir, systemische und psychodynamische Methoden führender Schulen zu kombinieren und so einen effektiven Coaching-Ansatz zu bieten.<br><br>
          # Upload image to `assets/media/` and reference the filename here
          image: prozess.jpg
          button:
            text: Kurzprofil
            url: https://hugoblox.com/templates
        - title: Coaching
          text: Hey. Schön, dass du da bist! Willkommen auf deinem Weg der Selbstentfaltung.<br><br> Als Coach ist es meine Aufgabe, Menschen auf ihrem Weg der persönlichen und beruflichen Entwicklung zu begleiten. Ein effektives Coaching setzt voraus, dass ich meine Klientinnen und Klienten ganzheitlich wahrnehme – mit ihrem Wesen, ihren individuellen Erfahrungen, ihren Stärken, ihren nonverbalen Signalen und ihren Herausforderungen. Auf dieser Basis kann ich kritisch hinterfragen, meine Irritationen benennen und gleichzeitig einfühlsam und zugewandt bleiben. Meine Erfahrung zeigt, dass jeder Mensch die notwendigen Antworten auf seine Herausforderungen bereits in sich trägt. Oft braucht es aber den gezielten Dialog und ein unterstützendes Gegenüber, um diese Antworten ans Licht zu bringen.<br><br> Meine Arbeit basiert auf der Metatheorie der Veränderung des Hephaistos Coaching Zentrums München. Diese theoretische Grundlage ermöglicht es mir, systemische und psychodynamische Methoden führender Schulen zu kombinieren und so einen effektiven Coaching-Ansatz zu bieten.<br><br>
          # feature_icon: bolt
          # features:
            # - "Dedicated support channel"
            # - "3,000+ users on Discord"
            # - "Share your site and get feedback"
          # Upload image to `assets/media/` and reference the filename here
          image: prozess.jpg
          # button:
            # text: Join Discord
            # url: https://discord.gg/z8wNYzb
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
