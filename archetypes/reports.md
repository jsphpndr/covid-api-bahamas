---

islands:

    np: &np New Providence
    gb: &gb Grand Bahama
    ab: &ab Abaco
    bim: &bim Bimini & Cat Cay
    el: &el Eleuthera
    bi: &bi Berry Islands
    ex: &ex Exuma
    in: &in Inagua
    an: &an Andros
    li: &li Long Island
    ci: &ci Cat Island
    ac: &ac Acklins
    cr: &cr Crooked Island
    ma: &ma Mayaguana
    ri: &ri Ragged Island
    ss: &ss San Salvador
    lp: &lp Location Pending

facilities:
  - facility: &doctors Doctor's Hospital
  - facility: &southBeach South Beach Acute Care and Referral Centre
  - facility: &pmh Princess Margaret Hospital
  - facility: &sandilands Sandilands Rehabilitation Centre
  - facility: &gbhs Grand Bahama Health Services

sex:
    m: &m Male
    f: &f Female

report:
  
  number: "{{ replace .Name "-" " " | title }}"
  date: {{ (now.AddDate 0 0 -1).Format "2006-01-02" }}
  datePublished: {{ .Date }}
  #dateModified:

  cases:

    byIsland:
      - island:
          name: *np 
          toDate: 
          new: 0
      - island:
          name: *gb 
          toDate: 
          new: 0
      - island:
          name: *ab 
          toDate: 
          new: 0
      - island:
          name: *bim
          toDate: 
          new: 0
      - island:
          name: *el 
          toDate: 
          new: 0
      - island:
          name: *bi
          toDate: 
          new: 0
      - island:
          name: *ex 
          toDate: 
          new: 0
      - island:
          name: *in 
          toDate: 
          new: 0
      - island:
          name: *an 
          toDate: 
          new: 0
      - island:
          name: *li 
          toDate: 
          new: 0
      - island:
          name: *ci 
          toDate: 
          new: 0
      - island:
          name: *ac 
          toDate: 
          new: 0
      - island:
          name: *cr 
          toDate: 
          new: 0
      - island:
          name: *ma 
          toDate: 
          new: 0
      - island:
          name: *ri 
          toDate: 0
          new: 0
      - island:
          name: *ss  
          toDate: 
          new: 0
      - island:
          name: *lp 
          toDate:
          new: 0
    
    toDateTotal: 
    newTotal: 
    
    ## Default is set to false.
    ifHistory: false
    
    historyOfTravel:
      - island:
          name: 
          new: 

    totalHistoryOfTravel: 

    bySex:
      - group:
          sex: *m
          new: 
      - group:
          sex: *f
          new: 

    inHospital:

      byFacility:
        - facility:
            island: *np
            name: *doctors
            total: 
            nonICU: 
            icu: 
        - facility:
            island: *np
            name: *southBeach
            total: 
            nonICU: 
            icu: 
        - facility:
            island: *np
            name: *pmh
            total: 
            nonICU: 
            icu: 
        - facility:
            island: *np
            name: *sandilands
            total: 0
            nonICU: 0
            icu: 0
        - facility:
            island: *gb
            name: *gbhs
            total: 
            nonICU: 
            icu: 
      
      totals:
        total:     
        nonICU: 
        icu: 

    active: 

    recovered: 
      toDate: 
      new: 
    
    fatalities:
      toDate: 
      unrelatedToDate: 
      underInvestigation: 

  ifReported: true

  reportedFatalities:
    
    - fatality: 
        age: 
        sex: 
        island: 
        date: 

  tests:
    toDate: 
    completed: 
    positive: 
    negative: 
    repeated: 
    inconclusive: 

###


draft: true
---
