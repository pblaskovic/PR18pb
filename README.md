### Projektna naloga

Analiza podatkov - TED talks
======================
V projektni nalogi analiziran je [TED talks dataset](https://www.kaggle.com/rounakbanik/ted-talks/data). Skup podataka TED talks 
vsebuje podatke o videih zbranihih na strani TED.com v obdobju do 21. septembra 2017.

## Opis
TED je neprofitna organizacija posvečena širjenju idej. Začetek zgodbe sega v leto 1984, ko se je v Kaliforniji odvil štiridnevni 
dogodek namenjen združitvi zamisli s treh različnih področij: tehnologije, zabave in oblikovanja = Technology, Entertainment, Design. 
Od tedaj TED deluje preko raznolikih mednarodnih pobud in aktivnosti. Na vsakoletni TED konferenci vodilni svetovni misleci in akterji 
svoje znanje posredujejo v 3 do 18 minut dolgih nastopih. Po dogodku so na TED.com njihovi govori brezplačno dostopni vsakomur.

## Vsebina
Skup podatkov vsebuje dve CSV datoteki:
- ted_main.csv - Vsebuje podatke o TED talk govornikima in TED Talk metadata.
- transcripts.csv - Vsebuje prepis in URL povezavo do vsakeg TED videa.

## Analiza podatkov
- Uporabljene Python libraries:
  - numpy
  - pandas
  - matplotlib
  - scipy

### Opis podatkov
 **ted_main.csv**

Naziv|Opis|Tip podatka
---|---|---
comments|The number of first level comments made on the talk|Numeric
description|A blurb of what the talk is about|String
duration|The duration of the talk in seconds|Numeric
event|The TED/TEDx event where the talk took place|String
film_date|The Unix timestamp of the filming|Numeric
languages|The number of languages in which the talk is available|Numeric
main_speaker|The first named speaker of the talk|String
name|The official name of the TED Talk. Includes the title and the speaker|String
num_speaker|The number of speakers in the talk|Numeric
published_date|The Unix timestamp for the publication of the talk on TED.com|Numeric
ratings|A stringified dictionary of the various ratings given to the talk (inspiring, fascinating, jaw dropping, etc.)|String
related_talks|A list of dictionaries of recommended talks to watch next|String
speaker_occupation|The occupation of the main speaker|String
tags|The themes associated with the talk|String
title|The title of the talk|String
url|The URL of the talk|String
views|The number of views on the talk|Numeric

 **transcript.csv**
 
Naziv|Opis|Tip podatka
---|---|---
transcript|The official English transcript of the talk|String
url|The URL of the talk|String


## Glavna prašanja
- Kateri so najbolj gledani i najbolja oceneni pogovori?
- Koliko je moških/ženskih govornikov? 
- Koje so najbolj pogoste teme govornikov? 
- Koliko so v povprečju dolgi govori, kateri so bolje oceneni, dolgi ali kratki? 
- V katerih krajih so posneti najbolj popularni pogovori? 
- V katerih mesecih so prikazovani najbolj populrani pogovorji? 
- Ali so TED talk-i med saboj nekako povezani? 
- Povezanost okupacije govornika z temo in ratingom pogovorja?

## Ugotovitve
1. **Do schools kill creativity?**
  - najbolj popularan TED talk, ima več kot 47 milijonov pogledov
  - najstarejši video, prvi uploadan na web stran (to vidimo iz originalnega dataseta ki je rasporejen po datumu objave na web strani 
  - posle videa **Militant atheism** je video z največ komentara
2. **Your body language may shape who you are**
  - drugi najbolj popularen video,ima več kot 43 milijonov pogledov
3.
  - to so edina 2 TED talka ki imajo več kot 40 milijonov pogledov
  - v povprečju videi so pregledani okol milijon in pol krat (1 698 297)
4. Najbolj pogoste **teme** govornikov
  - vsak video ima določene oznake (ang. Tags) oziroma o njegovoj vsebini
  - iz toga koliko je posamezan Tag pogost, vidimo koje teme se pogosto pojavljuju
  


## Usage Instructions
This is where you lay out all the commands available or how you make your software do its magic. This can be CLI, REST, powershell commands, etc. Remember to use the backtick characters to highlight code `such as this` or create sections of code using three backticks in a row
```
to do 
multiline
code
```

## Future
this is where you can add things you plan on adding to the future. this helps anyone wanting to contribute to know what they can help with. This is not a necessary thing to do if your project doesn't have a roadmap.
- Add these functions depending on necessity
  - thing 1
  - thing 2
  - thing 3
- Clean up the code
  - break out into multiple files
  - etc

## Contribution


