# Guide till Harvardmallen från Umeå universitet
[Documentation in English further down]
## Inledning
Den här dokumentationen beskriver hur du använder Zotero-stilmallen Umeå University - Harvard.

Generellt sätt så gäller det att inte ha med information som inte behövs. Alltså kan du behöva redigera en post i Zotero efter att du har importerat en referens. Till exempel så brukar URL-länkar följa med vid import och inkluderas ofta när du skapar en referens, men det är inte alltid du behöver ha med en länk i referensen.
## Hur du installerar stilen
1. Klicka på umea-university-harvard.csl ovan.
2. Välj ”Download raw file” uppe till höger.
3. Öppna Zotero-programmet och gå till Redigera > Inställningar > Källhänvisa.
4. Klicka på ”+” bredvid ”Få ytterligare stilar”. 
5. Bläddra till mappen där filen hämtats ned och klicka på csl-filen.
6. Klicka på OK.

Stilen är nu redo att börja användas. Om du vill skapa referenser direkt i ditt Worddokument behöver du först installera ett plugin. Du väljer sedan stilen under ”Document preferences” i Word.

Du hittar information om plugins för ordbehandlingsprogram på [Zoteros webbplats](https://www.zotero.org/support/word_processor_integration).
## Manuella justeringar du kan behöva göra
### Organisation som författare
Rapporter är ibland författade av en myndighet eller en annan organisation. Detsamma gäller för till exempel webbsidor, blogg- och foruminlägg och dataset, som kan sakna en namngiven författare.

Ange då organisationens namn i fältet för Författarens efternamn. Om du inte vill att organisationen omnämns en gång till, ta bort organisationen från fältet utgivare eller titel på sida/forum/uppslagsverk/ordbok (eller motsvarande).
### DOI för publikationstyperna avhandling, bok, kapitel i bok och rapport
Inte alla publikationstyper i Zotero har fältet DOI. Om du till exempel ska referera till ett exempelvis ett kapitel i en bok, fyller du i kapitlets DOI i fältet Extra:

Extra: DOI: 10.1007/978-3-030-63672-2_2
### Artikel-id i stället för sidnummer
Vissa tidskrifter har artikel-id i stället för sidnummer för artikel. Detta löser du genom att fylla i artikel-id i fältet Extra, till exempel:

Extra: Number: e20345

**Lämna fältet för sidnummer tomt.**
## Publikationstyper
### Offentligt tryck
#### Lagar och författningar
Använd typ Författning och fyll i endast följande information:
* Titel (blir kursiverad): Personuppgiftslag
* kort titel (om det finns)
* public law number: SFS 1998:204
* URL-länk och åtkomstdatum (om materialet har hämtats från internet).

**Lämna fältet för datum tomt.**

Referensen i referenslistan blir då:

SFS 1998:204. *Personuppgiftslag*. https://www.riksdagen.se/sv/dokument-och-lagar/dokument/svensk-forfattningssamling/personuppgiftslag-1998204_sfs-1998-204/ (Hämtad 2024-08-06).

…och i hänvisningen:

(SFS 1998:204)
#### Lagförarbete
För riksdagstryck, betänkanden, propositioner och offentliga utredningar, med mera, använd typen Lagförarbete och fyll endast i följande information:
* Titel (blir kursiverad): Nationell handlingsplan mot våld i nära relationer: delbetänkande
* kort titel (om det finns): Personsäkerhetsutredningen
* förarbetets referensnummer: SOU 2002:71
* URL-länk och åtkomstdatum (om materialet har hämtats från internet).

**Lämna fältet för datum tomt.**

Referensen i referenslistan blir då:

SOU 2002:71. Personsäkerhetsutredningen. *Nationell handlingsplan mot våld i nära relationer: delbetänkande*.

…och i hänvisningen:

(SOU 2002:71)
### Läroplaner
Ange som bok. Om en organisation (till exempel Skolverket) har författat publikationen, ange organisationen i fältet Efternamn och lämna fältet för Utgivare tomt.
### Arkivmaterial
Använd typen Manuskript och fyll i (om information finns):
* Eventuell författare (annars blir titel uppslagsordet)
* titel
* datum
* samling och plats i arkiv
* arkiv
* arkivort
* URL-länk och åtkomstdatum (om materialet har hämtats från internet).

Referensen i referenslistan blir då:

von Linné, C. (1748). Letter 22 August 1748, Uppsala to Jean François Séguier, Verona. L0942. Linnaean correspondence, Uppsala universitetsbibliotek. Uppsala. http://urn.kb.se/resolve?urn=urn:nbn:se:alvin:portal:record-224468 (Hämtad 2024-07-30).

…och i hänvisningen:

(von Linné 1748)

# Guide to the Umeå University Harvard style
## Introduction
This documentation guides how you use the Zotero style Umeå University - Harvard.

In general, it is important not to include information that is not needed. This means that you may need to edit a record in Zotero after you have imported a reference. For example, URL links are usually included in the import and are often automatically included in references, but you don't always need to include a link.
## How to install the style
1. Click on umea-university-harvard.csl above.
2. Select ”Download raw file” on the right.
3. Open the Zotero client and go to Edit > Preferences > Cite.
4. Click on “+” next to “Get additional styles”.
5. Browse to the downloads folder and click on the csl file.
6. Click OK.

The reference style is now ready for use. You must first install a plugin to create references in your Word document. Then, you can select the style under “Document preferences” in Word.

You can find information about plugins for word processors on the [Zotero website](https://www.zotero.org/support/word_processor_integration).
## Manual adjustments you may need to make
### Organisation as author
Some reports are sometimes authored by a government agency or another organisation. The same applies to web pages, blog posts, forum posts, and datasets, which may not have a named author.

In this case, enter the organisation's name in the Author surname field. If you do not want the organisation to be mentioned again, remove it from the publisher field or the title of the page/forum/encyclopaedia/dictionary/equivalent field.
### DOI for books, book chapters, reports, and theses
Not all publication types in Zotero have the DOI field. If you want to refer to a chapter in a book, for example, where the chapter itself has a DOI, enter the DOI in the Extra field:

Extra: DOI: 10.1007/978-3-030-63672-2_2
### Article number instead of page numbers
Some journals use article numbers instead of page numbers. You solve this by filling in the article number in the Extra field, for example:

Extra: Number: e20345

**Leave the pages field empty.**

## Publication types
### Public documents (Sweden)
This style covers Swedish legislation and other official documents in Sweden.

#### Legislation
Select the type Statute, and fill only in the following information:
* Title (will be cursive): Personuppgiftslag
* short title (if any)
* public law number: SFS 1998:204
* URL and access date (if the material has been accessed online).

**Leave the date field empty.**

The reference in the reference list will then be:

SFS 1998:204. *Personuppgiftslag*. https://www.riksdagen.se/sv/dokument-och-lagar/dokument/svensk-forfattningssamling/personuppgiftslag-1998204_sfs-1998-204/ (Accessed 2024-08-06).

...and the citation:

(SFS 1998:204)

#### Bill
Select the type Bill for motions, propositions, official reports from the government, etc., and fill only in the following information:
* Title (will be cursive): Nationell handlingsplan mot våld i nära relationer: delbetänkande
* short title (if any): Personsäkerhetsutredningen
* bill number: SOU 2002:71
* URL and access date (if the material has been accessed online).

**Leave the date field empty.**

The reference in the reference list will then be:

SOU 2002:71. Personsäkerhetsutredningen. *Nationell handlingsplan mot våld i nära relationer: delbetänkande*.

...and the citation:

(SOU 2002:71)

### Archival material
Use the type Manuscript and fill in (if the information is available):
* Author, if any (otherwise, the title becomes the reference word)
* title
* date
* collection and location in the archive
* archive
* archive place
* URL link and date of access (if the material has been accessed online).

The reference in the reference list will then be:

Linnaeus, C. (1748). Letter 22 August 1748, Uppsala to Jean François Séguier, Verona. L0942. Linnaean correspondence, Uppsala University Library. Uppsala. http://urn.kb.se/resolve?urn=urn:nbn:se:alvin:portal:record-224468 (Accessed 2024-07-30).

...and the citation:

(von Linné 1748)
