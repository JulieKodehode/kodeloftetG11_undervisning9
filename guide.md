# Template Guide

## HTML

- Header: Logo, søkfelt, innlogging og navigasjon.
- Main: Ulike seksjoner for ulik informasjons fremheving.
  - Section: Seksjon med full bredde, seksjon som er todelt, seksjoner delt opp i "kort".
- Footer: Sosiale medier, navigasjon, kreditasjon og personvern (offentlige sider).

## CSS

- "Kort" som skal se lik ut kan ha samme class-navn.
- Skille mellom seksjoner med fargebytte

# Prosjekt guide

- Artikkel stil med fokus tekst og bilder
  - Semantiske løsninger for tekst og bilde element
  - Plasserings løsninger for tekst og bilde element

Main
Section = flex flex-direction row
  div = flex flex-direction column
    h1 og p til venstre 
  img til hørgre

Section = flex flex-direction row
  img til venstre
  div = flex flex-direction column
    h1 og p til høyre