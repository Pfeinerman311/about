---
title: Parker Feinerman
---

# Education

## Cornell University, College of Engineering
_August 2021_  \| Ithaca, NY
- Bachelor of Science, Computer Science \| Minor in Business, Dyson School of Business
  
## Jericho Senior High School
_June 2016_ \| Jericho, NY  
- **Honors & Awards:** AP Scholar w/ Distinction \| National Honor Society \| Spanish Honor Society \| Toshiba ExploraVision \| DuPont Essay Challenge

# Skills

Programming Languages | Platforms/Databases | Design & IDE Tools | Operating Systems
---- | ---- | ---- | ----
Java | Google Cloud Platform | Visual Studio Code | Windows
Python | AWS | IntelliJ | macOS
C/C++ | Git | Atom | Linux (Debian/Ubuntu)
OCaml | Wordpress | Eclipse | WIndows Server
R | MySQL | Komodo | Android
HTML | Zapier | Logisim
CSS | Pipedrive | Diptrace
SQL | Infusionsoft | Arduino IDE
JSON | Oracle | Autodesk
ROBOTC | | Adobe Creative Cloud

# Relevant Experience

## 311PARK LLC
_**Founder & CEO**_  
_September 2012 - Present_ \| Syosset, NY  
  
**Services Include:** Technical Consulting, Invention Contracting, and Media Production for clients in FinTech, Professional Services, and other industries  
- Technical Consulting includes software development, IT and network security, pen testing, website design, and server management.
- Invention Contracting includes individually tailored assisted invention design and prototyping.
- Media Production includes content creation and incubation, graphic design, and production partnerships.


# Projects

## CS 3110 - Poker



### Overview


### Individual Contributions


### Code Snippet
```
type rank = Two | Three | Four | Five | Six | Seven | Eight | Nine
          | Ten | Jack | Queen | King | Ace

type suit = Clubs | Diamonds | Hearts | Spades

type card = rank * suit

type player = {
  name : string;
  id : int;
  active: bool;
  stack : int;
  hole_cards: card list
}

let ranks =
  [Two; Three; Four; Five; Six; Seven; Eight; Nine; Ten; 
   Jack; Queen; King; Ace]

type hand_tp = Royal_Flush | Straight_Flush | Four_Kind | Full_House
             | Flush | Straight | Three_Kind | Two_Pair | Pair
             | High_Card

type hand = {
  tp : hand_tp;
  cards : card list;
}
```

### Demo

![poker](https://user-images.githubusercontent.com/22283357/128093580-75dde6c6-db0d-499f-aabf-b65d6e293b96.gif)
