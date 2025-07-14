# Fields needed for WB2JN

We need to test out the below and see what the results would look like on a number of Ensembles. The test can just be a checklist check and see if the attributes or texts exist and have data needed. After this we can do other tests. We shsould check 9 example Ensembles.

  1. Solitude - https://www.deckenmalerei.eu/10885d10-c5b7-11e9-b6fd-d99e1ba53a95
  2. Bad Pyrmont, Schloss Pyrmont - https://www.deckenmalerei.eu/b462cec2-5ade-45da-be2e-759323274a52 
  3. https://www.deckenmalerei.eu/6d7bc9b2-1d68-417b-acf8-43035863c91f
  4. https://www.deckenmalerei.eu/c38d1922-cc2a-4e5f-90ad-f4c474baf2d8
  5. https://www.deckenmalerei.eu/07358bb5-b969-4a1b-93ed-289d49e854a3 
  6. https://www.deckenmalerei.eu/7c269630-f8f7-419a-82b7-73edf92bffe8
  7. https://www.deckenmalerei.eu/fa6290dc-3339-4ce6-b4ae-02017979d994 
  8. https://www.deckenmalerei.eu/5dc41007-0057-4904-a126-6f36aaef086f 
  9. https://www.deckenmalerei.eu/0db9d590-c57c-11e9-a249-1d82ad4f6e4d 

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

## Image cycle (Bildzyklus)

  - Photo
  - Name
  - hat Maler
  - Date
  - ist dokumentiert in: [Textteil]

Links to:
  - Painting

