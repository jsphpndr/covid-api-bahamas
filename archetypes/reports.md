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

title: {{ replace .Name "-" " " | title }} ### DO NOT TOUCH ###
date: {{ .Date }} ### DO NOT TOUCH ###
###############################################################
## START EDITING HERE ... 
report: ### DO NOT TOUCH ###
  
  number: {{ replace .Name "-" " " | title }}
  # The date format is YYYY-DD-MM. So, October 6, 2021 would be written as 2021-06-10.
  date: # FILL REPORT DATE
  contributor: # Are you a contributor? Fill in your name for recognition.

  cases: ### DO NOT TOUCH ###

    byIsland: ### DO NOT TOUCH ###
      ##### NEW PROVIDENCE #########
      - island: ### DO NOT TOUCH ###
          name: *np ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### GRAND BAHAMA ###########
      - island: ### DO NOT TOUCH ###
          name: *gb ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### ABACO ##################
      - island: ### DO NOT TOUCH ###
          name: *ab ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### BIMINI ##################
      - island: ### DO NOT TOUCH ###
          name: *bim ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### ELEUTHERA ##############
      - island: ### DO NOT TOUCH ###
          name: *el ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### BERRY ISLANDS ##########
      - island: ### DO NOT TOUCH ###
          name: *bi ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### EXUMA ##################
      - island: ### DO NOT TOUCH ###
          name: *ex ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### INAGUA #################
      - island: ### DO NOT TOUCH ###
          name: *in ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### ANDROS #################
      - island: ### DO NOT TOUCH ###
          name: *an ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### LONG ISLAND ############
      - island: ### DO NOT TOUCH ###
          name: *li ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### CAT ISLAND #############
      - island: ### DO NOT TOUCH ###
          name: *ci ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### ACKLINS #################
      - island: ### DO NOT TOUCH ###
          name: *ac ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### CROOKED ISLAND #########
      - island: ### DO NOT TOUCH ###
          name: *cr ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### MAYAGUANA ##############
      - island: ### DO NOT TOUCH ###
          name: *ma ### DO NOT TOUCH ###
          toDate: 
          new: 0
      ##### RAGGED ISLAND ##########
      - island: ### DO NOT TOUCH ###
          name: *ri ### DO NOT TOUCH ###### DO NOT TOUCH ###
          toDate: 0
          new: 0
      ##### SAN SALVADOR ############
      - island: ### DO NOT TOUCH ###
          name: *ss ### DO NOT TOUCH ###### DO NOT TOUCH ### 
          toDate: 
          new: 0
      ##### LOCATION PENDING ########
      - island: ### DO NOT TOUCH ###
          name: *lp ### DO NOT TOUCH ###
          toDate:
          new: 0
    ##### TOTAL CONFIRMED CASES ##########
    toDateTotal:
    ##### BREAKDOWN OF NEWLY CONFIRMED CASES ##########
    newTotal: 
    
    # There are usually no cases with travel history in these  
    # reports, so the default for ifTravelHistory is set to false. 
    # However, if there are reported cases, set ifTravelHistory to true.
    ifTravelHistory: false
    ##### HISTORY OF TRAVEL ######
    historyOfTravel: ### DO NOT TOUCH ###

        byIsland:  ### DO NOT TOUCH ###
            # Copy and paste this object based on the
            # corresponding number of deaths reported.
            # If five deaths, copy five times then fill
            # in data.
            - island: ### DO NOT TOUCH ###
                name:
                new: 

        total: 0
    
    ##### GENDER OF NEWLY CONFIRMED CASES ########
    bySex: ### DO NOT TOUCH ###
      #############################
      - group: ### DO NOT TOUCH ###
          sex: *m ### DO NOT TOUCH ###
          new: 
      #############################
      - group: ### DO NOT TOUCH ###
          sex: *f ### DO NOT TOUCH ###
          new: 
      #############################

    ##### HOSPITALIZATIONS #####
    inHospital: ### DO NOT TOUCH ###

      byFacility: ### DO NOT TOUCH ###
        ################################
        - facility: ### DO NOT TOUCH ###
            island: *np ### DO NOT TOUCH ###
            name: *doctors ### DO NOT TOUCH ###
            total: 
            nonICU: 
            icu: 
        ################################
        - facility: ### DO NOT TOUCH ###
            island: *np ### DO NOT TOUCH ###
            name: *southBeach ### DO NOT TOUCH ###
            total: 
            nonICU: 
            icu: 
        ################################
        - facility: ### DO NOT TOUCH ###
            island: *np ### DO NOT TOUCH ###
            name: *pmh ### DO NOT TOUCH ###
            total: 
            nonICU: 
            icu: 
        ################################
        - facility: ### DO NOT TOUCH ###
            island: *np ### DO NOT TOUCH ###
            name: *sandilands ### DO NOT TOUCH ###
            total: 0
            nonICU: 0
            icu: 0
        ################################
        - facility: ### DO NOT TOUCH ###
            island: *gb ### DO NOT TOUCH ###
            name: *gbhs ### DO NOT TOUCH ###
            total: 
            nonICU: 
            icu: 
      ################################
      totals: ### DO NOT TOUCH ###
        total:     
        nonICU: 
        icu: 

    ##### ACTIVE CASES & RECOVERIES #####
    active: 

    recovered: ### DO NOT TOUCH ### 
      toDate: 
      new: 

    ##### DEATHS #####
    fatalities: ### DO NOT TOUCH ###
      toDate: 
      unrelatedToDate: 
      underInvestigation: 

  ##### REPORTED DEATHS #### AGE / SEX / ISLAND / DATE OF DEATH #####
  # There are usually deaths reported in these reports, so the 
  # default for ifReported is set to true. However, if there are 
  # no reported cases, set ifReported to false.
  ifReported: true

  reportedFatalities: ### DO NOT TOUCH ###
    
    # Copy and paste this object based on the
    # corresponding number of deaths reported.
    # If five deaths, copy five times then fill
    # in data.

    # The date format is YYYY-DD-MM. So, October 6, 2021 would be written as 2021-06-10.
    - fatality: ### DO NOT TOUCH ###
        age: 
        sex: 
        island: 
        date: 

  ##### TESTS COMPLETED
  tests: ### DO NOT TOUCH ###
    ##### TOTAL OF RT-PCR TESTS COMPLETED #####
    toDate: 
    ##### TOTAL OF RT-PCR TESTS COMPLETED TODAY #####
    completed: 
    ##### RESULTS #####
    positive: 
    ##### RESULTS #####
    negative: 
    ##### RESULTS #####
    repeated: 
    ##### RESULTS #####
    inconclusive: 

###


draft: true
---
