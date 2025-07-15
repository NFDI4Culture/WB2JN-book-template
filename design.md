# Fields needed for WB2JN

![alt text](https://gitlab.com/-/project/66804787/uploads/212829095f88477709e21d4b360c4394/Unbenanntes_Diagramm-Seite-2.drawio_1_.png "Title")

Diagrams: https://gitlab.com/nfdi4culture/computational-publishing-service/wb2jn/-/issues/28

We need to test out the below and see what the results would look like on a number of Ensembles. The test can just be a checklist check and see if the attributes or texts exist and have data needed. After this we can do other tests. We shsould check 9 example Ensembles.

  1. Solitude - https://www.deckenmalerei.eu/10885d10-c5b7-11e9-b6fd-d99e1ba53a95
  2. Bad Pyrmont, Schloss Pyrmont - https://www.deckenmalerei.eu/b462cec2-5ade-45da-be2e-759323274a52 
  3. Altshausen, Landkomturei des Deutschen Ordens - https://www.deckenmalerei.eu/6d7bc9b2-1d68-417b-acf8-43035863c91f
  4. Bad Buchau, Fürstabtei - https://www.deckenmalerei.eu/c38d1922-cc2a-4e5f-90ad-f4c474baf2d8
  5. Rastatt-Förch, Schloss Favorite - https://www.deckenmalerei.eu/07358bb5-b969-4a1b-93ed-289d49e854a3 
  6. Weikersheim, Schloss - https://www.deckenmalerei.eu/7c269630-f8f7-419a-82b7-73edf92bffe8
  7. Aicholding, Hofmarkschloss - https://www.deckenmalerei.eu/fa6290dc-3339-4ce6-b4ae-02017979d994 
  8. Egloffstein, Schlosskirche St. Bartholomäus - https://www.deckenmalerei.eu/5dc41007-0057-4904-a126-6f36aaef086f 
  9. Gundelfingen, Münzmühle - https://www.deckenmalerei.eu/0db9d590-c57c-11e9-a249-1d82ad4f6e4d 

These are all the things for which are needed as 'things' that then would each have a group of attributes. My thinking is that if we have these things and their 'has part' or 'is part of' attribute in the tree, then this allows to select them from a tree and say which things and thing attributes we want to use.

The 'has part' or 'is part of' tree links are not listed here.

  - Castle / Palace (Ensemble)
  - Photo
  - Building
  - Building part
  - Text part
  - Room
  - Painting
  - Image cycle (Bildzyklus) (because these are another way that paintings have been marked up and are not marked up as being paintings. We don't have to include them if its a problem)

## Castle / Palace (Ensemble)

Attributes or text needed:

  - Name
  - Adresse
  - Typ
  - Photo
  - ist dokumentiert in: [Textteil]

Links to:

 - Building

## Photo

Attributes or text needed:

To provide the photo image for rendering and provide caption information.

  - Image URL
  - Name
  - Bildnachweis
  - Urheber
  - Lizenz
  - Repositorium

## Building

Attributes or text needed:

  - Photo
  - Name
  - Adresse
  - Typ
  - ist dokumentiert in: [Textteil]

Links to:  
  - Room
  - Room sequence/"Space sequence"
  - Building part

## Building part

Attributes or text needed:

  - Photo
  - Name
  - Bundesland
  - Typ 
  - ist dokumentiert in: [Textteil]

Links to:  
  - Room
  - Room Sequence

## Text part

Attributes or text needed (this is not so easy):

  - Header in page
  - Textteil ID
  - body text

## Room

  - Image URL
  - Name
  - Typ 
  - Photo 
  - ist dokumentiert in: [Textteil]
  - Date

Links to:  
  - Image cycle
  - Painting

## Painting

  - Photo
  - Name
  - hat Maler
  - Date
  - ist dokumentiert in: [Textteil]

## Painting part 

  - Photo
  - Name
  - hat Maler
  - Date
  - ist dokumentiert in: [Textteil]

## Image cycle (Bildzyklus)

  - Photo
  - Name
  - hat Maler
  - Date
  - ist dokumentiert in: [Textteil]

Links to:
  - Painting

--- 

# Example overview

## 1. Solitude - https://www.deckenmalerei.eu/10885d10-c5b7-11e9-b6fd-d99e1ba53a95

### Castle / Palace (Ensemble)

Attributes or text needed:

  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] Photo
  - [x] ist dokumentiert in: [Textteil]

Links to:

 - [x] Building

### Photo

Attributes or text needed:

To provide the photo image for rendering and provide caption information.

  - [x] Image URL
  - [x] Name
  - [x] Bildnachweis
  - [x] Urheber
  - [x] Lizenz
  - [x] Repositorium

### Building https://www.deckenmalerei.eu/770108e0-c5c0-11e9-bae7-59743fb301a8

Attributes or text needed:

  - [x] Photo
  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [ ] Room sequence/"Space sequence"
  - [x] Building part

### Building part https://www.deckenmalerei.eu/9fc7e0a0-c5c0-11e9-bae7-59743fb301a8

Attributes or text needed:

  - [x] Photo
  - [x] Name
  - [ ] Bundesland
  - [x] Typ 
  - [x] ist dokumentiert in: [Textteil]

Links to:  
  - [x] Room
  - [ ] Room Sequence

### Text part

Attributes or text needed (this is not so easy):

  - [ ] Header in page
  - [ ] Textteil ID
  - [ ] body text

### Room https://www.deckenmalerei.eu/12eb95e0-c5c1-11e9-bae7-59743fb301a8

  - [x] Name
  - [x] Typ 
  - [x] Photo 
  - [x] ist dokumentiert in: [Textteil]
  - [x] Date

Links to:  
  - [ ] Image cycle
  - [x] Painting

### Painting https://www.deckenmalerei.eu/a49355f0-c5c1-11e9-bae7-59743fb301a8

  - [x] Photo
  - [x] Name
  - [x] hat Maler
  - [x] Date
  - [x] ist dokumentiert in: [Textteil]

### Image cycle (Bildzyklus)

  - [ ] Photo
  - [ ] Name
  - [ ] hat Maler
  - [ ] Date
  - [ ] ist dokumentiert in: [Textteil]

Links to:
  - [ ] Painting

## 2. Bad Pyrmont, Schloss Pyrmont - https://www.deckenmalerei.eu/b462cec2-5ade-45da-be2e-759323274a52 

### Castle / Palace (Ensemble)

Attributes or text needed:

  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] Photo
  - [x] ist dokumentiert in: [Textteil]

Links to:

 - [x] Building

### Photo

Attributes or text needed:

To provide the photo image for rendering and provide caption information.

  - [x] Image URL
  - [x] Name
  - [x] Bildnachweis
  - [x] Urheber
  - [x] Lizenz
  - [x] Repositorium

### Building https://www.deckenmalerei.eu/cb7e6b7d-cdb7-41ea-a373-1ae5d22c881a

Attributes or text needed:

  - [x] Photo
  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [x] Room sequence/"Space sequence"
  - [ ] Building part

### Building part

Attributes or text needed:

  - [ ] Photo
  - [ ] Name
  - [ ] Bundesland
  - [ ] Typ 
  - [ ] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [ ] Room Sequence

### Room sequence https://www.deckenmalerei.eu/da4cbde5-d7d9-4b7e-8571-015baa04416e


  - [x] Name
  - [x] Typ 
  - [x] Photo 
  - [x] ist dokumentiert in: [Textteil]
  - [x] Date

Links to:  
  - [x] Room

### Text part

Attributes or text needed (this is not so easy):

  - [ ] Header in page
  - [ ] Textteil ID
  - [ ] body text

### Room

  - [x] Name
  - [x] Typ 
  - [x] Photo 
  - [x] ist dokumentiert in: [Textteil]
  - [x] Date

Links to:  
  - [x] Image cycle
  - [ ] Painting

### Painting https://www.deckenmalerei.eu/819bb070-fcfe-4ed0-8aef-80070a2bdcf5

  - [x] Photo
  - [x] Name
  - [x] hat Maler
  - [x] Date
  - [x] ist dokumentiert in: [Textteil]

### Image cycle (Bildzyklus) https://www.deckenmalerei.eu/18f02c52-115f-4fc4-8179-f8ee6c79344d

  - [x] Photo
  - [x] Name
  - [x] hat Maler
  - [x] Date
  - [x] ist dokumentiert in: [Textteil]

Links to:
  - [x] Painting

## 3. Altshausen, Landkomturei des Deutschen Ordens - https://www.deckenmalerei.eu/6d7bc9b2-1d68-417b-acf8-43035863c91f

### Castle / Palace (Ensemble)

Attributes or text needed:

  - [ ] Name
  - [ ] Adresse
  - [ ] Typ
  - [ ] Photo
  - [ ] ist dokumentiert in: [Textteil]

Links to:

 - [x] Building

### Photo

Attributes or text needed:

To provide the photo image for rendering and provide caption information.

  - [x] Image URL
  - [x] Name
  - [x] Bildnachweis
  - [x] Urheber
  - [x] Lizenz
  - [x] Repositorium

### Building https://www.deckenmalerei.eu/ffe17bf7-ed12-4462-8936-4f47e2b53363

Attributes or text needed:

  - [x] Photo
  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] ist dokumentiert in: [Textteil]

Links to:  
  - [x] Room
  - [ ] Room sequence/"Space sequence"
  - [ ] Building part

### Building part https://www.deckenmalerei.eu/23532a95-033b-4f38-b69f-e9206bea1e3b

Attributes or text needed:

  - [ ] Photo
  - [ ] Name
  - [ ] Bundesland
  - [ ] Typ 
  - [ ] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [ ] Room Sequence

### Room sequence 

  - [ ] Name
  - [ ] Typ 
  - [ ] Photo 
  - [ ] ist dokumentiert in: [Textteil]
  - [ ] Date

Links to:  
  - [ ] Room

### Text part

Attributes or text needed (this is not so easy):

  - [ ] Header in page
  - [ ] Textteil ID
  - [ ] body text

### Room https://www.deckenmalerei.eu/9971a1a0-a59e-46ed-9801-80c24f7e9044

  - [x] Name
  - [x] Typ 
  - [x] Photo 
  - [x] ist dokumentiert in: [Textteil]
  - [x] Date

Links to:  
  - [ ] Image cycle
  - [x] Painting

### Painting https://www.deckenmalerei.eu/8e5f3ffd-af13-4529-8748-9c8941140e02

  - [x] Photo
  - [x] Name
  - [x] hat Maler
  - [x] Date
  - [x] ist dokumentiert in: [Textteil]

### Image cycle (Bildzyklus)

  - [ ] Photo
  - [ ] Name
  - [ ] hat Maler
  - [ ] Date
  - [ ] ist dokumentiert in: [Textteil]

Links to:
  - [ ] Painting

## 4. Bad Buchau, Fürstabtei - https://www.deckenmalerei.eu/c38d1922-cc2a-4e5f-90ad-f4c474baf2d8

### Castle / Palace (Ensemble)

Attributes or text needed:

  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] Photo
  - [x] ist dokumentiert in: [Textteil]

Links to:

 - [x] Building

### Photo

Attributes or text needed:

To provide the photo image for rendering and provide caption information.

  - [x] Image URL
  - [x] Name
  - [x] Bildnachweis
  - [x] Urheber
  - [x] Lizenz
  - [x] Repositorium

### Building https://www.deckenmalerei.eu/48554093-289c-492a-a060-735d4e8971e8

Attributes or text needed:

  - [x] Photo
  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] ist dokumentiert in: [Textteil]

Links to:  
  - [x] Room
  - [ ] Room sequence/"Space sequence"
  - [ ] Building part

### Building part

Attributes or text needed:

  - [ ] Photo
  - [ ] Name
  - [ ] Bundesland
  - [ ] Typ 
  - [ ] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [ ] Room Sequence

### Room sequence 

  - [ ] Name
  - [ ] Typ 
  - [ ] Photo 
  - [ ] ist dokumentiert in: [Textteil]
  - [ ] Date

Links to:  
  - [ ] Room

### Text part

Attributes or text needed (this is not so easy):

  - [ ] Header in page
  - [ ] Textteil ID
  - [ ] body text

### Room https://www.deckenmalerei.eu/25496253-99e6-4177-b8fd-1c632fe67586

  - [x] Name
  - [x] Typ 
  - [x] Photo 
  - [x] ist dokumentiert in: [Textteil]
  - [x] Date

Links to:  
  - [x] Image cycle
  - [ ] Painting


### Image cycle (Bildzyklus) https://www.deckenmalerei.eu/309f413a-c6dd-4269-a000-c8e9dc95b58b

  - [x] Photo
  - [x] Name
  - [x] hat Maler
  - [ ] Date
  - [x] ist dokumentiert in: [Textteil]

Links to:
  - [x] Painting

### Painting https://www.deckenmalerei.eu/7d7a40cb-9d89-48da-a609-98d43a7dcf18

  - [x] Photo
  - [x] Name
  - [x] hat Maler
  - [ ] Date
  - [x] ist dokumentiert in: [Textteil]


## 5. Rastatt-Förch, Schloss Favorite - https://www.deckenmalerei.eu/07358bb5-b969-4a1b-93ed-289d49e854a3 

### Castle / Palace (Ensemble)

Attributes or text needed:

  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] Photo
  - [x] ist dokumentiert in: [Textteil]

Links to:

 - [x] Building

### Photo

Attributes or text needed:

To provide the photo image for rendering and provide caption information.

  - [x] Image URL
  - [x] Name
  - [x] Bildnachweis
  - [x] Urheber
  - [x] Lizenz
  - [x] Repositorium

### Building https://www.deckenmalerei.eu/118b2450-7755-40ff-8f6c-2a53b5990e90

Attributes or text needed:

  - [x] Photo
  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [x] Room sequence/"Space sequence"
  - [ ] Building part

### Building part

Attributes or text needed:

  - [ ] Photo
  - [ ] Name
  - [ ] Bundesland
  - [ ] Typ 
  - [ ] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [ ] Room Sequence

### Room sequence 

  - [x] Name
  - [x] Typ 
  - [x] Photo 
  - [x] ist dokumentiert in: [Textteil]
  - [x] Date

Links to:  
  - [ ] Room
  - **Nothing**

### Text part

Attributes or text needed (this is not so easy):

  - [ ] Header in page
  - [ ] Textteil ID
  - [ ] body text

### Room

  - [ ] Image URL
  - [ ] Name
  - [ ] Typ 
  - [ ] Photo 
  - [ ] ist dokumentiert in: [Textteil]
  - [ ] Date

Links to:  
  - [ ] Image cycle
  - [ ] Painting

### Painting

  - [ ] Photo
  - [ ] Name
  - [ ] hat Maler
  - [ ] Date
  - [ ] ist dokumentiert in: [Textteil]

### Image cycle (Bildzyklus)

  - [ ] Photo
  - [ ] Name
  - [ ] hat Maler
  - [ ] Date
  - [ ] ist dokumentiert in: [Textteil]

Links to:
  - [ ] Painting

## 6. Weikersheim, Schloss - https://www.deckenmalerei.eu/7c269630-f8f7-419a-82b7-73edf92bffe8


### Castle / Palace (Ensemble)

Attributes or text needed:

  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] Photo
  - [x] ist dokumentiert in: [Textteil]

Links to:

 - [x] Building

### Photo

Attributes or text needed:

To provide the photo image for rendering and provide caption information.

  - [x] Image URL
  - [x] Name
  - [x] Bildnachweis
  - [x] Urheber
  - [x] Lizenz
  - [x] Repositorium

### Building https://www.deckenmalerei.eu/3fd3e7eb-1041-480f-9be5-840c7ae050d9

Attributes or text needed:

  - [x] Photo
  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] ist dokumentiert in: [Textteil]

Links to:  
  - [x] Room
  - [ ] Room sequence/"Space sequence"
  - [ ] Building part

### Building part

Attributes or text needed:

  - [ ] Photo
  - [ ] Name
  - [ ] Bundesland
  - [ ] Typ 
  - [ ] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [ ] Room Sequence

### Room sequence 

  - [ ] Name
  - [ ] Typ 
  - [ ] Photo 
  - [ ] ist dokumentiert in: [Textteil]
  - [ ] Date

Links to:  
  - [ ] Room

### Text part

Attributes or text needed (this is not so easy):

  - [ ] Header in page
  - [ ] Textteil ID
  - [ ] body text

### Room https://www.deckenmalerei.eu/9597dd58-0170-46fe-bfb4-09287e03611f

  - [x] Name
  - [x] Typ 
  - [x] Photo 
  - [x] ist dokumentiert in: [Textteil]
  - [x] Date

Links to:  
  - [x] Image cycle
  - [ ] Painting

### Image cycle (Bildzyklus)

  - [x] Photo
  - [x] Name
  - [ ] hat Maler
  - [x] Date
  - [x] ist dokumentiert in: [Textteil]

Links to:
  - [x] Painting
  
### Painting https://www.deckenmalerei.eu/b9e7af30-b216-49ce-bca3-54b50a336e60

  - [x] Photo
  - [x] Name
  - [ ] hat Maler
  - [x] Date
  - [x] ist dokumentiert in: [Textteil]


## 7. Aicholding, Hofmarkschloss - https://www.deckenmalerei.eu/fa6290dc-3339-4ce6-b4ae-02017979d994 

### Castle / Palace (Ensemble)

Attributes or text needed:

  - [ ] Name
  - [ ] Adresse
  - [ ] Typ
  - [ ] Photo
  - [ ] ist dokumentiert in: [Textteil]

Links to:

 - [ ] Building

### Photo

Attributes or text needed:

To provide the photo image for rendering and provide caption information.

  - [ ] Image URL
  - [ ] Name
  - [ ] Bildnachweis
  - [ ] Urheber
  - [ ] Lizenz
  - [ ] Repositorium

### Building

Attributes or text needed:

  - [ ] Photo
  - [ ] Name
  - [ ] Adresse
  - [ ] Typ
  - [ ] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [ ] Room sequence/"Space sequence"
  - [ ] Building part

### Building part

Attributes or text needed:

  - [ ] Photo
  - [ ] Name
  - [ ] Bundesland
  - [ ] Typ 
  - [ ] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [ ] Room Sequence

### Room sequence 

  - [ ] Name
  - [ ] Typ 
  - [ ] Photo 
  - [ ] ist dokumentiert in: [Textteil]
  - [ ] Date

Links to:  
  - [ ] Room

### Text part

Attributes or text needed (this is not so easy):

  - [ ] Header in page
  - [ ] Textteil ID
  - [ ] body text

### Room

  - [ ] Image URL
  - [ ] Name
  - [ ] Typ 
  - [ ] Photo 
  - [ ] ist dokumentiert in: [Textteil]
  - [ ] Date

Links to:  
  - [ ] Image cycle
  - [ ] Painting

### Painting

  - [ ] Photo
  - [ ] Name
  - [ ] hat Maler
  - [ ] Date
  - [ ] ist dokumentiert in: [Textteil]

### Image cycle (Bildzyklus)

  - [ ] Photo
  - [ ] Name
  - [ ] hat Maler
  - [ ] Date
  - [ ] ist dokumentiert in: [Textteil]

Links to:
  - [ ] Painting
# 8. Egloffstein, Schlosskirche St. Bartholomäus - https://www.deckenmalerei.eu/5dc41007-0057-4904-a126-6f36aaef086f 


## Castle / Palace (Ensemble)

Attributes or text needed:

  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] Photo
  - [x] ist dokumentiert in: [Textteil]

Links to:

 - [x] Building

## Photo

Attributes or text needed:

To provide the photo image for rendering and provide caption information.

  - [x] Image URL
  - [x] Name
  - [x] Bildnachweis
  - [x] Urheber
  - [x] Lizenz
  - [x] Repositorium

## Building https://www.deckenmalerei.eu/83b1da10-f430-492e-b918-8eadb8fd1af8

Attributes or text needed:

  - [x] Photo
  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [ ] Room sequence/"Space sequence"
  - [ ] Building part

## Building part

Attributes or text needed:

  - [ ] Photo
  - [ ] Name
  - [ ] Bundesland
  - [ ] Typ 
  - [ ] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [ ] Room Sequence

## Room sequence 

  - [ ] Name
  - [ ] Typ 
  - [ ] Photo 
  - [ ] ist dokumentiert in: [Textteil]
  - [ ] Date

Links to:  
  - [ ] Room

## Text part

Attributes or text needed (this is not so easy):

  - [ ] Header in page
  - [ ] Textteil ID
  - [ ] body text

## Room https://www.deckenmalerei.eu/11f652c8-0f55-4272-9412-9d6978b0686e

  - [x] Name
  - [x] Typ 
  - [x] Photo 
  - [x] ist dokumentiert in: [Textteil]
  - [x] Date

Links to:  
  - [ ] Image cycle
  - [x] Painting

## Painting https://www.deckenmalerei.eu/95e32516-0031-467a-acc3-e0a0007a7efd

  - [x] Photo
  - [x] Name
  - [ ] hat Maler
  - [x] Date
  - [x] ist dokumentiert in: [Textteil]

Links to:  
  - [x] Painting Part

## Painting part https://www.deckenmalerei.eu/e45d9b2e-a890-499c-98df-97fc312eabac

  - [x] Photo
  - [x] Name
  - [x] hat Maler
  - [x] Date
  - [x] ist dokumentiert in: [Textteil]

## Image cycle (Bildzyklus)

  - [ ] Photo
  - [ ] Name
  - [ ] hat Maler
  - [ ] Date
  - [ ] ist dokumentiert in: [Textteil]

Links to:
  - [ ] Painting

# 9. Gundelfingen, Münzmühle - https://www.deckenmalerei.eu/0db9d590-c57c-11e9-a249-1d82ad4f6e4d 


## Castle / Palace (Ensemble)

Attributes or text needed:

  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] Photo
  - [x] ist dokumentiert in: [Textteil]

Links to:

 - [x] Building

## Photo

Attributes or text needed:

To provide the photo image for rendering and provide caption information.

  - [x] Image URL
  - [x] Name
  - [x] Bildnachweis
  - [x] Urheber
  - [x] Lizenz
  - [x] Repositorium

## Building https://www.deckenmalerei.eu/79d04660-c57c-11e9-a249-1d82ad4f6e4d

Attributes or text needed:

  - [ ] Photo
  - [x] Name
  - [x] Adresse
  - [x] Typ
  - [x] ist dokumentiert in: [Textteil]

Links to:  
  - [x] Room
  - [ ] Room sequence/"Space sequence"
  - [ ] Building part

## Building part

Attributes or text needed:

  - [ ] Photo
  - [ ] Name
  - [ ] Bundesland
  - [ ] Typ 
  - [ ] ist dokumentiert in: [Textteil]

Links to:  
  - [ ] Room
  - [ ] Room Sequence

## Room sequence 

  - [ ] Name
  - [ ] Typ 
  - [ ] Photo 
  - [ ] ist dokumentiert in: [Textteil]
  - [ ] Date

Links to:  
  - [ ] Room

## Text part

Attributes or text needed (this is not so easy):

  - [ ] Header in page
  - [ ] Textteil ID
  - [ ] body text

## Room https://www.deckenmalerei.eu/9d83cd90-c57f-11e9-a249-1d82ad4f6e4d

  - [x] Name
  - [x] Typ 
  - [x] Photo 
  - [x] ist dokumentiert in: [Textteil]
  - [x] Date

Links to:  
  - [ ] Image cycle
  - [x] Painting

## Painting https://www.deckenmalerei.eu/dac0cc9f-0b61-4e4e-8bba-510e053dc978

  - [x] Photo
  - [x] Name
  - [ ] hat Maler
  - [ ] Date
  - [x] ist dokumentiert in: [Textteil]

## Image cycle (Bildzyklus)

  - [ ] Photo
  - [ ] Name
  - [ ] hat Maler
  - [ ] Date
  - [ ] ist dokumentiert in: [Textteil]

Links to:
  - [ ] Painting

