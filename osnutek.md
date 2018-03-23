# TED talks dataset

Ta dataset vsebujeje informacije o vseh avdio-video posnetkih TED talk-ov, prenesenih na uradno spletno mesto TED.com do 
21. septembra 2017. Glavni dataset (ted_main.csv) vsebuje informacije o vseh pogovorih, vključno s številom ogledov, številom
komentarjev, opisima in naslovima. Drugi dataset (transcripts.csv) vsebuje prepise za vse pogovore, ki so na voljo na TED.com.
Opisano je 2550 TED talk-ov.

V ti nalogi bi poskušala odgovorit na vprašanja kot so:
Kateri so najbolj gledani i najbolja oceneni pogovori
Koliko je moških/ženskih govornikov
Koje so najbolj pogoste teme govornikov
Koliko so v povprečju dolgi govori, kateri so bolje oceneni, dolgi ali kratki
V katerih krajih so posneti najbolj popularni pogovori
V katerih mesecih so prikazovani najbolj populrani pogovorji
Ali so TED talk-i med saboj nekako povezani
Povezanost okupacije govornika z temo in ratingom pogovorja

Vir: https://www.kaggle.com/rounakbanik/ted-talks/data
V podatkima so dva .csv file: ted_main.csv in transcripts.csv


OBLIK PODATKOV:

ted_main.csv
-- This table contains 2550 rows and 17 columns.

comments
The number of first level comments made on the talk
Numeric

description
A blurb of what the talk is about
String

duration
The duration of the talk in seconds
Numeric

event
The TED/TEDx event where the talk took place
String

film_date
The Unix timestamp of the filming
Numeric

languages
The number of languages in which the talk is available
Numeric

main_speaker
The first named speaker of the talk
String

name
The official name of the TED Talk. Includes the title and the speaker.
String

num_speaker
The number of speakers in the talk
Numeric

published_date
The Unix timestamp for the publication of the talk on TED.com
Numeric

ratings
A stringified dictionary of the various ratings given to the talk (inspiring, fascinating, jaw dropping, etc.)
String

related_talks
A list of dictionaries of recommended talks to watch next
String

speaker_occupation
The occupation of the main speaker
String

tags
The themes associated with the talk
String

title
The title of the talk
String

url
The URL of the talk
String

views
The number of views on the talk
Numeric




transcript.csv
-- This table contains 2467 rows and 2 columns

transcript
The official English transcript of the talk.
String

url
The URL of the talk
String
