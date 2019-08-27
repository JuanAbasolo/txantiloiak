# Txantiloiak

Momentuz hau ez da aproba hutsa baino.

**Helburua**: Holakoren batean hemen izatea, RStudio erabilita, behar direan txantiloiak, helburu desberdinekin.

Instalagarriak izateko sortu dut (helburua txantiloien zerrendan hemengoak agertzea)

1. `devtools` paketea erabili behar da.
2. R kontsolan `devtools::install("txantiloiak")` idatzi behar da goiko karpetan dagoela (berta-bertan huts egiten dau)
3. Instalaten dauala dinoan mezua leidu behar da
4. R berrabiarazi.
    *Session>Restart R*  edo
    `Ktrl+Shift+F10`
5. RMarkdown dokumentu barria sortu, *templates* aukereagaz.

---

Instalau on-line zuzenean:

```R
devtools::install_github('JuanAbasolo/txantiloiak/txantiloiak')
```

Momentuz errore mezu batek urteten dau. *Don't worry, install happy*.

---

## Txantiloi barriak sortzeko

1. Euki eskura behar dan guztia
2. Antolatu. Horretarako karpeta egitura bat sortu behar da  
    `dir.create("inst/rmarkdown/templates/noberak.nahi.dauan.izena/skeleton", recursive = TRUE)`  
    Danakin ez naz ahalegindu, baina badakit egiturak holako izenetako batzuk derrigorrez behar dituana.
3. Beherengo karpetaren ixena *skeleton* izango da eta bertan sartu behar da RMarkdown dokumentu tuneau hori, *skeleton.Rmd* ixena emonta
4. Aurreko karpetan, adibideko *noberak.nahi.dauan.izena* izenekoan, sortu behar da testu lauko fitxategia, izena izango duena `template.yaml`.  
    Barruko informazioa lerro bakarrean: *name: Ipini nahi jakon izena*
5. Instalau eta gero txantiloien aukeretan agertuko da aurreko puntuko *name* horretakoa.

---

## ToDo

- [ ] Irudiak gehitzeko modua aurkitu
- [x] `.csl` fitxategiak eta `.bib` fitxategiak gehitzeko modua aurkitu

