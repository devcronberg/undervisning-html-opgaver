# HTML opgave i semantik

Denne opgave skal give dig lidt øvelse i at skabe en HTML side med semantiske opmærkninger.

- Start med en standard HTML skabelon (! + tab)
- Der skal være en header-opmærkning, som består af en h1-overskrift med teksten "Min app" eller lignende. 
  - h1-opmærkningen skal have en id-attribut med værdien "ov"
- Der skal være en section-opmærkning som består af to article-opmærkninger.
  - I hver article-opmærkning skal der være en p-opmærkning med teksterne "Dette er afsnit 1" og "Dette er afsnit 2"
  - De to p-opmærkninger skal begge have en class-egenskab med værdien "tekst"
- Der skal afsluttes med en footer-opmærkning, som består af en h5-opmærkning med teksten "Dette er en footer"

Altså noget ala:

  - body
    - header
      - h1
        - Min App
    - article
      - section
        - p
          - Dette er afsnit 1
      - section
        - p
          - Dette er afsnit 2
    - footer
      - h5
        - Dette er en footer

HUSK - siden skal kunne valideres gennem W3C.

Se eventuelt min [løsning](index.html)

## Ekstra

Skab eventuelt en ny side som ikke benytter header, section, article, footer - men i stedet div-opmærkninger med css-klasser. Sådan tilføjede man semantik tidligere, men de nye opmærkninger giver bedre forståelse og ensartethed.

Se mit forslag til [løsning](index2.html).