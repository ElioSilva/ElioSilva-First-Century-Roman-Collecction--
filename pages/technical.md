---
title: Technical Documentation
layout: about
permalink: /technical.html
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---
# Technical Documentation
{% include feature/nav-menu.html sections="Items Chosen;Imaging Standards;Metadata Standards;" %}
## Items Chosen
All the elements that have been chosen for this collection have been completely digitized and have received OCR treatment with ABBYY FineReader 15, from scanners located on the 1st floor of the east tower from Wells Library, IU Bloomington. This means that all PDF files are searchable, both within the files themselves and via the site's search bar. However, the PDF file needs to be opened to view the text. Because it was entered earlier, the OCR has been able to correct all errors. Likewise, the quality of the OCR is generally quite good, adding to the quality of the most current editions of most digitized books. It should be noted that since most of the names are uncommon or are in Latin, they have not been corrected, despite being marked as an observation by the OCR.

## Metadata Standards
The metadata for this project concentrates on accurately representing a variety of features of the items that are helpful to its bibliographic description and other features that might be of interest to scholars or readers. For this reason, the metadata scheme uses a selection of Dublin Core elements. The values of individual elements are subject to both custom and established controlled vocabularies and content standards such as  Internet MIMEtype.  

Below is an explanation of what Dublin Core and text item type elements are used and what standards have been applied to their input.

### Dublin Core elements  
#### Title - required, 1 value allowed
The title element contains the title of the work. This information is taken from the title page of the history book. Titles are formatted according to Spanish capitalization conventions where only the first word and any proper nouns are capitalized.Also it includes accent marks or tíldes, if necessary.  

Examples: Orígenes de Roma, Guerras Ibéricas 

#### Creator - required, multiple values allowed
The creator element is used to denote the author. Authors are listed in the pamphlet novels by their given name or alternate name.

Example: Suetonio 

#### Description - required
The description element contains a short description of the content of the book. 

#### Date - required, 1 value allowed
Date element contains the value of the date of publication which is important to include in any sort of bibliographic item. The dates are formatted according to the [W3C date format](https://www.w3.org/TR/NOTE-datetime) which allows for dates to be inputted in this way:  
- YYYY-MM-DD
- YYYY-MM
- YYYY

All of the items included in this digital library have a full month, year, day publication date since it was a weekly publication, meaning that all of the dates are in the YYYY-MM-DD format.  

Example: 2007-02-05 to denote february 05, 2007  

#### Language - required, multiple values allowed
Although all the books are translated into Spanish, in some cases they use phrases or words in classical Latin. There are also books that are bilingual editions, which one page is in Spanish and another in Classical Latin (although it does not happen in most cases). 

Examples: spa 


#### Subject - required, multiple values allowed
The subject field contains topic(s) related to the Roman classical books. Inspired by the construction of Library Congress, my own subject headings will be in the form of a word, a phrase, or a name, all assigned with or without subdivisions.

Examples:
i.	Simple nouns: Julio César; Las Galias; Rúbicón
ii.	Compound phrases: Alea Iacta Est; Repetit italiam; perfectique utrunque
iii.	Complex phrases: Conspiraciones en Roma; Los idus de Marzo; Retraro y papel personal de Julio César.

#### File Format - required 1 value allowed
All items in the collection should be made into Pdf.according to the Media Types from Internet Assigned numbers Authority  and Mime types,
 items were saved as author name, book title and the file extension!

Example:a.	suetonio_vidasdeloscesares.pdf

#### Lenght - required 1 value allowed
the number of pages each book contains. It covers from the first page with writing, either introduction or preface,and first five pages. It does not count any blank sheets.

Example: 9pp

#### Series - required 1 value allowed
The genre series under which a classical book was published. First word of the title and the author’s name are capitlized. Those include accent marks or tíldes
 
 Example: Vidas de los Doce Césares

#### Dimensions - required, 1 value allowed
The dimension is the size of the physical book. Every book was measured before being digitized, through ruler, Sturdy flat object (such as a book or piece of cardboard) or Flat surface. State dimension in inches. Format as Win x Lin where W=horizontal measurement and L=vertical measurement.

Example: 4.72 x 7.09in

#### Translator - required , multiple values allowed
All the published works are translated. The translator or contributor  is listed in this field in order to not be confused with the original author in the creator element. Like the creator element, the values of the translator element are formatted according to the [Library of Congress Name Authority File](https://id.loc.gov/authorities/names.html).

For Example: Castro de Castro, David

#### Rights - required, 1 value allowed
I have permission from Book publishing companies to post few pages from every book in the website. However, it doesnt mean those are public domain. First, as long as those are not full book , it will be allowed to be posted for non-commercial, educaciona and reserach use only. Its is the responsability of the user to obtain the permission from the copyright owners (publishing companies). 

Bellow you can enter the Legal Notice section of any of the three publishers' websites:

[Alianza Editorial](https://www.alianzaeditorial.es/aviso-legal/)

[Akal Ediciones](https://www.akal.com/p/aviso-legal/)

[Gredos Ediciones](https://www.rba.es/general/aviso-legal-libros_179)

## Acknowledgments
First, I would like to mention Dr. John Walsh and Associate instructor Alex Wingate for their valuable help and feedback that I received for the sake of this project. I thank all the people who believed in me since I came to the US to start a new phase of my life. Some of them are no longer with me, but they will still be in my heart. I will demonstrate with this work that it is possible to go far doing what one is passionate about.
