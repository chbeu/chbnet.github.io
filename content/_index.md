---
# Leave the homepage title empty to use the site title
title: ".: Christine Bauer :."
date: 2023-08-04
type: landing
sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: christine-bauer
      text: |-
        Christine Bauer ist eine Saxophonistin und Sängerin, die sich dem Rock und Pop-Genre verschrieben hat, um die Füße der Welt zum Tanzen zu bringen.<br><br>
        Das musikalische Repertoire reicht von erdigem Rock, groovigem Funk, über rhythmisierenden Soul, bis hin zu gefühlvollem Blues.<br><br>
        Während Covers in eigenen Arrangements zu einem neuen Gesamtpaket verschnürt werden, zeichnen sich die eigenen Songs durch eingängige Melodien und emotionsgeladene Texte aus.<br><br>
        Gemeinsam mit der Würze der MitmusikerInnen wird eine musikalische Suppe gekocht, die so noch nicht gegessen wurde.<br><br>
        Taste it – Like it – Shake it!
        {style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #4698C3 0%, #EA4892 30%, #FFFFFF 60%, #000000 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}
    design:
      columns: '1'
      background:
        color: dark
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: top/_MG_8848_cropped.jpg
          filters:
            brightness: 0.7
          fit: cover
          position: center
          parallax: false
      css_class: d-flex fullscreen align-items-center
  - block: portfolio
    id: portfolio
    content:
      title: Portfolio
      filters:
        folders:
          - portfolio
    design:
      columns: '2'
      background:
        color: dark
        text_color_light: true
        view: showcase
        flip_alt_rows: false
  - block: portfolio
    id: projekte
    content:
      title: Projekte / Formationen
      filters:
        folders:
          - projekte
    design:
      columns: '2'
      background:
        color: dark
        text_color_light: true
        view: showcase
        flip_alt_rows: false
  - block: markdown
    id: fotos
    content:
      title: Fotos
      text: |-
            {{< gallery album="gallery" >}}
    design:
      columns: '2'
      background:
        color: dark
        text_color_light: true
  - block: markdown
    id: media
    content:
      title: Media
      text: |-
            ## Zum Hören
            Moments – Musik & Text: Manfred Leikermoser, Christine Bauer, Lukas Schistek, Christian Hierhold, Peter Roberts, Robin Sars<br><br>
            Alright – Musik & Text: Christine Bauer, Christian Hierhold, Peter Roberts<br><br>
             ## Zum Hören und Sehen
            {{< youtube uBIwxdkX490 >}}
            {{< youtube TgKjNew3liE >}}
            {{< video src="videos/popak_klangketten_klar_20170607.mp4" controls="yes" >}}
            {{< youtube ssgdea0ejto >}}
            {{< youtube jKaRr846It4 >}}
            {{< youtube 4oXq0DBa62Q >}}
            {{< youtube PtceQY21GgM >}}
    design:
      columns: '2'
      background:
        color: dark
        text_color_light: true
  - block: markdown
    id: bio
    content:
      title: Bio
      text: |-
            Mit vier kam die Blockflöte und dann war Christine nicht mehr zu stoppen.<br><br>
            Nach einigen Jahren Unterricht am Akkordeon wechselte Christine mit zwölf ans Saxophon, um sich davon nicht mehr losreißen zu können. Zwei Jahre Studium des Jazz-Saxophon am Konservatorium der Stadt Wien bei Thomas Huber. Seminare und Workshops ua. bei Ilse Riedler, Martin Fuss, Michael Erian, Robert Friedl, Andy Middleton, Roman Schwaller,…<br><br>
            Diverse Stile des Populargesangs ua. bei Karin Maria Bauer, Ingrid Diem, Nina Braith und Mel Verez. Unterricht im klassischen Gesang bei Anita Götz. Sprechtraining ua. bei Lydia Rathkolb, Karin Steger und Martha Wedral.<br><br>
            Ensemble- und Band-Workshops ua. bei Rens Newland, Christoph Cech, Johannes Herrlich, Daniel Nösig, Christian Havel, Rob Bargad, Agostino Di Giorgio, Mario Gonzi, Georg Gruber, Christian Maurer,…
    design:
      columns: '2'
      background:
        color: white
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: top/8755-1-2000x1500.jpg
          filters:
            brightness: 0.7
          fit: cover
          position: center
          parallax: false
  - block: markdown
    id: credits
    content:
      title: Credits
      text: |-
            ## Formationen
            ua. Bigband Utrecht, Waves on Fire, Amanda Palmer and the Grand Theft Orchestra, SaxSuperheroes, My Little Blues Band, The New Live Collective, Sonic 99, Big Bang Big Band, Fritz Hujer’s Jazz La Vie, Jazz Connection 22, Blankoscheck, Undercover Big Band Vösendorf, Kirchenchor Neusimmering, Alpha Jazz Band feat. Victoria Quattlebaum, Alpha Dance Band, Vienna Big One Band, Mindless, Musicians Society Jazz Band, Musicians Society Wind Band, Juvina Sextett, Jugendmusik Lackenbach.<br><br>
            ## Internationale Auftritte
            ua. in Brasilien, China, Deutschland, Großbritannien, Italien, Niederlande, Österreich, Schweden, Ungarn, USA.
    design:
      columns: '2'
      background:
        color: white
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: top/_MG_9094.JPG
          filters:
            brightness: 0.7
          fit: cover
          position: center
          parallax: false
  - block: collection
    id: posts
    content:
      title: News
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - post
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: showcase
      # Choose single or dual column layout
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Kontakt
      subtitle: ''
      text: ''
      # Contact details - edit or remove options as needed
      email: info@christinebauer.net
      address:
        #street: 
        city: Wien
        #postcode: ''
        country: Austria
      # Automatically link email and phone or display them just as text?
      autolink: false
    design:
      columns: '2'
      background:
        color: dark
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: top/20170823_11.JPG
          filters:
            brightness: 0.7
          fit: cover
          position: center
          parallax: false
---

