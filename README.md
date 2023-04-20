# prep_n_clean

# Lines 1-1643 fully reviewed and revised except for 2 sections:

# Problems:

# 1) event_crime_qual (Lines 1162-1216)
# # for 20 article news event_crime_qual wasn't registered.
# # only 19 of those 20 can/have been identified
# # original code included 4604 (the 20th value) however the event associated with idrow 4604 was coded as no originally (not an "NA -> recoded as no")

# 2) event_attackerid (lines 1477-1513)
# # for 47 article news event_attackerid wasn't registered.
# # only 46 of those 47 can/have been identified

# Major revisions:

# 1) The total number of rows to include (is.na(all_mxlynch_rawR$news_include)): 9350 (differs from original coders: 9274)

# 2)
# revised:
# news_include
# No  Yes
# 5541 3809

# original code:
# news_include
# No   Yes 
# 5478 3796 

# Other Notes:
# all of the "hard-coded" lines that remain are coded as such because there is no other option





