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
            für Privatpersonen
        - statistic: ""
          description: ""
        - statistic: "Business Coaching"
          description: |
            für Fach- und Führungskräfte
    design:
      # Section background color (CSS class)
      css_class: "bg-white"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
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
          image: about-me-a.jpeg
          button:
            text: Kurzprofil
            url: https://drive.google.com/file/d/1WhV_CgYvuU3_PBB62VICofMgFtbJ-iOx/view?usp=sharing
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
          image: process-bg-blue.jpg
        - title: Personal Coaching
          text: Immer mehr Menschen berichten, wie ihnen eine gezielte individuelle Unterstützung half, ihre privaten und beruflichen Chancen zu nutzen und ein erfülltes, selbstbestimmtes Leben zu führen.<br><br> Mein Personal Coaching bietet dir einen vertraulichen Rahmen, um dein Anliegen – sei es persönliche Weiterentwicklung, Beziehungsfragen, Krisenbewältigung oder Lebensbalance – gezielt zu klären.<br><br> Wir konzentrieren uns auf das, was dir wichtig ist – deine Wünsche und Bedürfnisse – und arbeiten mit dem, was du im Hier und Jetzt erlebst und ausdrückst. Gemeinsam beleuchten wir auch herausfordernde Aspekte, um herauszufinden, wie sie dich möglicherweise hemmen oder blockieren. So gewinnst du Klarheit über deine Situation und entwickelst neue Perspektiven, die deinen Handlungsspielraum erweitern und dich spürbare Fortschritte im Alltag erleben lassen.<br><br>
          # feature_icon: bolt
          # features:
            # - "Dedicated support channel"
            # - "3,000+ users on Discord"
            # - "Share your site and get feedback"
          # Upload image to `assets/media/` and reference the filename here
          image: personal.png
          # button:
            # text: Join Discord
            # url: https://discord.gg/z8wNYzb
        - title: Business Coaching
          text: In einer dynamischen Arbeitswelt ist kontinuierliche Weiterentwicklung unerlässlich. Mein Business Coaching richtet sich an Fach- und Führungskräfte sowie Unternehmerinnen und Unternehmer, die sich beruflich weiterentwickeln und ihr Unternehmen auf das nächste Level bringen möchten.<br><br> Im Fokus steht die Selbstreflexion, um innere Muster zu erkennen und tiefgreifende Veränderungen zu bewirken. Ich unterstütze dich dabei, deine Stärken zu fördern und eine authentische Führungsidentität zu entwickeln. Mit gezielten Übungen gewinnst du innere Klarheit und erreichst deine Ziele effizienter.<br><br> Ich arbeite mit einem systemischen Ansatz, der die Wechselwirkungen und Dynamiken in deinem Unternehmen umfassend berücksichtigt. Auf diese Weise analysieren wir die innerbetrieblichen Prozesse und entwickeln darauf basierend Lösungen, die positive Veränderungen fördern.<br><br>
          # feature_icon: bolt
          # features:
            # - "Dedicated support channel"
            # - "3,000+ users on Discord"
            # - "Share your site and get feedback"
          # Upload image to `assets/media/` and reference the filename here
          image: business.png
          # button:
            # text: Join Discord
            # url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-image-paragraph
    id: bewegung
    content:
      items:
        - title: Bewegung
          text: |
            In Coaching-Prozessen stoßen wir oft an die Grenzen des Verstandes. Manchmal reichen Worte allein nicht aus, um tiefsitzende Gefühle oder blockierende Muster zu lösen. Es sind die Momente, in denen Gespräche ins Leere laufen oder festgefahrene Denkmuster uns daran hindern, weiterzukommen. Hier ist es wichtig, dass wir den Körper in den Coaching-Prozess einbeziehen. Denn der Körper vergisst nicht.<br><br>
            
            Unser Körper trägt unausgesprochene Emotionen, Erinnerungen und Erfahrungen in sich. Er speichert, was wir erlebt haben, auch wenn unser Verstand es längst verdrängt hat. Wenn wir auf die Signale unseres Körpers hören, eröffnen sich oft neue Wege. Der Körper erlaubt uns dann, das auszudrücken, was wir fühlen, und das zunächst Unaussprechliche nimmt Gestalt an.<br><br>
            
            Mit körperorientierten Methoden wie Atemtechniken, Achtsamkeitsübungen oder Yoga nutzen wir in Einzelsitzungen die Weisheit deines Körpers, um Blockaden zu lösen. So wird der Körper zum Schlüssel für deine authentische Veränderung und dein Wachstum.<br><br>
          # Upload image to `assets/media/` and reference the filename here
          image: bewegung.png
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-image-paragraph
    id: netzwerk
    content:
      items:
        - title: Netzwerk
          text: |
            **Hey. Hier ist mein Netzwerk!**<br><br>
            
            Wachstum entsteht durch starke Verbindungen und gegenseitige Unterstützung. Mein Ziel ist es, ein vertrauensvolles Netzwerk aufzubauen, um gemeinsam Herausforderungen zu meistern und nachhaltige Erfolge zu erzielen. Netzwerken bedeutet für mich, langfristige Beziehungen zu pflegen, regelmäßige Treffen zu fördern und kontinuierlich im Austausch zu stehen, um voneinander zu lernen und zu wachsen.<br><br>
            
            Zur Erweiterung meiner Expertise bilde ich mich an renommierten Schulen fort und nehme regelmäßig an Supervisionen teil. Dadurch erhalte ich wertvolle Impulse und neue Perspektiven. Besonders wichtig ist mir der Austausch mit den Kolleginnen und Kollegen des Hephaistos Coaching Zentrums München, die sich durch einen reflektierten und praxisnahen Ansatz auszeichnen. Das hilft mir, aktuelle Herausforderungen besser zu verstehen und innovative Lösungen zu entwickeln.<br><br>
            
            Denn Lernen hört nie auf! Die kontinuierliche Weiterentwicklung meiner Fähigkeiten ist entscheidend, um optimal auf individuelle Bedürfnisse einzugehen und effektive Veränderungsprozesse zu fördern.<br><br>
          # Upload image to `assets/media/` and reference the filename here
          image: network.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: cta-card
    id: kontakt
    content:
      title: Schön, dass du dich meldest!
      text: Gerne erkläre ich dir in einem unverbindlichen Erstgespräch meine Arbeitsweise und den Ablauf eines Coachings.<br><br> Du kannst mich gerne telefonisch oder per E-Mail kontaktieren, in der Regel antworte ich innerhalb von drei Werktagen.<br><br> Ich freue mich darauf, dich kennenzulernen!
      button:
        text: Schreib mir
        url: mailto:hey.marinaberger@gmail.com
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
