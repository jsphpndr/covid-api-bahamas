---

islands:
  np: &np New Providence
  gb: &gb Grand Bahama
  el: &el Eleuthera
  ab: &ab Abaco
  ex: &ex Exuma
  an: &an Andros
  bim: &bim Bimini
  li: &li Long Island & Rum Cay
  bi: &bi Berry Islands
  ci: &ci Cat Island
  in: &in Inagua
  ss: &ss San Salvador
  ac: &ac Acklins
  cr: &cr Crooked Island
  ma: &ma Mayaguana
  # ri: &ri Ragged Island

update:

  number: {{ replace .Name "-" " " | title }}
  date: 
  # Uncomment .Date to record data modifications
  datePublished: {{ .Date }}
  #dateModified: 

  doses:

    aggregate:
      total: 
      first: 

    byIsland:
      - island:
          name: *np
          first: 
          second: 
      - island:
          name: *gb
          first: 
          second: 
      - island:
          name: *el
          first: 
          second: 
      - island:
          name: *ab
          first: 
          second: 
      - island:
          name: *ex
          first: 
          second: 
      - island:
          name: *an
          first: 
          second: 
      - island:
          name: *bim
          first: 
          second: 
      - island:
          name: *li
          first: 
          second: 
      - island:
          name: *bi
          first: 
          second: 
      - island:
          name: *ci
          first: 
          second: 
      - island:
          name: *in
          first: 
          second: 
      - island:
          name: *ss
          first: 
          second: 
      - island:
          name: *ac
          first: 
          second: 
      - island:
          name: *cr
          first: 
          second: 
      - island:
          name: *ma
          first: 
          second: 


  full: 

  abroad: 



draft: true
---

