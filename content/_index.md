---
# Leave the homepage title empty to use the site title
title: ".: Christine Bauer :."
date: 2023-08-04
type: landing
sections:
  - block: markdown
    id: about
    content:
      title: Christine Bauer
      subtitle: Saxophone & Vocals
      text: |-
        Christine Bauer ist eine Saxophonistin und Sängerin, die sich dem Rock und Pop-Genre verschrieben hat, um die Füße der Welt zum Tanzen zu bringen.<br>
         {style="margin-left:150px; margin-top:90px; padding: 0 15px 0 15px; font-size: 1.1rem; color: #ffffff; background: linear-gradient(to right, rgba(0, 0, 0, .35) 0%, rgba(70, 152, 195, .35) 100%);"}
        Das musikalische Repertoire reicht von erdigem Rock, groovigem Funk, über rhythmisierenden Soul bis hin zu gefühlvollem Blues.<br>
         {style="margin-left:150px; padding: 0 15px 0 15px; font-size: 1.1rem; color: #ffffff; background: linear-gradient(to right, rgba(0, 0, 0, .35) 0%, rgba(234, 72, 146, .3) 100%);"}
        Während Covers in eigenen Arrangements zu einem neuen Gesamtpaket verschnürt werden, zeichnen sich die eigenen Songs durch eingängige Melodien und emotionsgeladene Texte aus.<br>
         {style="margin-left:150px; padding: 0 15px 0 15px; font-size: 1.1rem; color: #ffffff; background: linear-gradient(to right, rgba(0, 0, 0, .35) 0%, rgba(70, 152, 195, .35) 100%);"}
        Gemeinsam mit der Würze der Mitmusiker:innen wird eine musikalische Suppe gekocht, die so noch nicht gegessen wurde.<br>
         {style="margin-left:150px; margin-bottom:60px; padding: 0 15px 0 15px; font-size: 1.1rem; color: #ffffff; background: linear-gradient(to right, rgba(0, 0, 0, .35) 0%, rgba(234, 72, 146, .3) 100%);"}
    design:
      columns: '2'
      background:
        color: light
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: top/8755.jpeg
          filters:
            brightness: 0.8
          fit: cover
          position: center
          parallax: false
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
        color: light
        text_color_light: false
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
        color: light
        text_color_light: false
        view: showcase
        flip_alt_rows: false
  - block: markdown
    id: fotos
    content:
      title: Fotos
      text: |-
            <br><br>
            {{< gallery album="gallery" >}}
    design:
      columns: '2'
      background:
        color: light
        text_color_light: false
  - block: markdown
    id: media
    content:
      title: Media
      text: |-
            ## Zum Hören
            {style="color: #000000;"}
            Moments---Musik & Text: Manfred Leikermoser, Christine Bauer, Lukas Schistek, Christian Hierhold, Peter Roberts, Robin Sars
            {{< audio src="audio/09_Moments.mp3" >}}
            Alright---Musik & Text: Christine Bauer, Christian Hierhold, Peter Roberts<br><br>
            {{< audio src="audio/08_Alright.mp3" >}}
             ## Zum Hören und Sehen
            {style="color: #000000;"}
            {{< youtube PtceQY21GgM >}}
            {{< youtube uBIwxdkX490 >}}
            {{< youtube zQ_-mo2gArQ >}}
            {{< youtube ssgdea0ejto >}}
            {{< youtube TgKjNew3liE >}}
            {{< video src="videos/popak_klangketten_klar_20170607.mp4" controls="yes" poster="videos/popak_klar_still.jpeg" >}}
            {{< youtube jKaRr846It4 >}}
            {{< youtube 4oXq0DBa62Q >}}
    design:
      columns: '2'
      background:
        color: light
        text_color_light: false
  - block: markdown
    id: bio
    content:
      title: Bio
      text: |-
            Mit vier kam die Blockflöte und dann war Christine nicht mehr zu stoppen.<br><br>
            Nach fünf Jahren Unterricht am Akkordeon wechselte Christine mit zwölf ans Saxophon, um sich davon nicht mehr losreißen zu können. Zwei Jahre Studium des Jazz-Saxophon am Konservatorium der Stadt Wien bei Thomas Huber. Seminare und Workshops ua. bei Ilse Riedler, Martin Fuss, Michael Erian, Robert Friedl, Andy Middleton, Roman Schwaller,…<br><br>
            Diverse Stile des Populargesangs ua. bei Karin Maria Bauer, Ingrid Diem, Nina Braith und Mel Verez. Unterricht im klassischen Gesang bei Anita Götz. Sprechtraining ua. bei Lydia Rathkolb, Karin Steger und Martha Wedral.<br><br>
            Klavier bei Iva Zabkar, Julia Radschiner und Rudi Wilfer.<br><br>
            Ensemble- und Band-Workshops ua. bei Rens Newland, Christoph Cech, Johannes Herrlich, Daniel Nösig, Christian Havel, Rob Bargad, Agostino Di Giorgio, Mario Gonzi, Thomas Huber, Georg Gruber, Christian Maurer,…
    design:
      columns: '2'
      background:
        color: white
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: top/_MG_9094.jpeg
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
          filename: top/chb_voc-min.jpg
          filters:
            brightness: 0.6
          fit: cover
          position: center
          parallax: false
  - block: collection
    id: posts
    content:
      title: News
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
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
      background:
        color: light
        text_color_light: false
      # Choose a listing view
      view: compact
      # Choose single or dual column layout
      columns: '2'
  - block: contact
    id: kontakt
    content:
      title: Kontakt
      subtitle: ''
      text: |-
        **Sie planen einen Event?**<br><br>
        Buchungsanfragen, Anregungen, Kritiken etc.---
        Melden Sie sich einfach <br>per E-mail.
         {style="margin-right:530px; padding: 15px 15px 15px 15px; color: #ffffff; background: linear-gradient(to right, rgba(0, 0, 0, .35) 0%, rgba(70, 152, 195, .35) 100%);"}
      # Contact details - edit or remove options as needed
      email: info@christinebauer.net
      address:
        #street: 
        city: Wien
        #postcode: '1120'
        country: Austria
      # Automatically link email and phone or display them just as text?
      autolink: false
    design:
      columns: '2'
      background:
        color: light
        text_color_light: true
        image:
          # Add your image background to `assets/media/`.
          filename: top/050_christine-bauer_fuer-liwest_by_kurt-hoerbst.jpg
          filters:
            brightness: 0.7
          fit: cover
          position: center
          parallax: false
---
