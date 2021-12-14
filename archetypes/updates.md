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
  rc: &rc Rum Cay

title: {{ replace .Name "-" " " | title }}
weight: {{ replace .Name "-" " " | title }}
date:

update:

  number: {{ replace .Name "-" " " | title }}

  full: 

  abroad: 

  pfizer: true
  pfizernote: Pfizer two dose vaccination introduced to numbers between Saturday, Aug 07, 2021 and  Saturday, Aug 14, 2021 period.

  jj: true
  jjnote: Johnson & Johnson single dose vaccination introduced to numbers between Sat, Sep 4, 2021 and Fri, Sep 10, 2021 period.
  
  doses:

    aggregate:
      total: 
      first: 

    byIsland:
      - island:
          name: *np
          first: 
          fully: 0
      - island:
          name: *gb
          first: 
          fully: 0
      - island:
          name: *el
          first: 
          fully: 0
      - island:
          name: *ab
          first: 
          fully: 0
      - island:
          name: *ex
          first: 
          fully: 0
      - island:
          name: *an
          first: 
          fully: 0
      - island:
          name: *bim
          first: 
          fully: 0
      - island:
          name: *li
          first: 
          fully: 0
      - island:
          name: *bi
          first: 
          fully: 0
      - island:
          name: *ci
          first: 
          fully: 0
      - island:
          name: *in
          first: 
          fully: 0
      - island:
          name: *ss
          first: 
          fully: 0
      - island:
          name: *ac
          first: 
          fully: 0
      - island:
          name: *cr
          first: 
          fully: 0
      - island:
          name: *ma
          first: 
          fully: 0
    #   - island:
    #       name: *rc
    #       first: 
    #       fully: 0

draft: true
---

