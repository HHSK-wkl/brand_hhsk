# Brand extension voor HHSK


## Installeren

In R
```r
quarto::quarto_add_extension("HHSK-wkl/brand_hhsk")
```

Of in de terminal

```bash
quarto add HHSKwkl/brand_hhsk
```

Dit installeert de brand onder de `_extensions` directory. 

## Gebruik template

In R. 

NB  ij gebruik van de R-functie moet de map leeg zijn.


```r
quarto::quarto_use_template("HHSK-wkl/brand_hhsk")
```

Of in de terminal

```bash
quarto use template HHSKwkl/brand_hhsk
```

Dit download te template en installeert (optioneel) de brand onder de `_extensions` directory. 


## Gebruik extension

Voor correct gebruik van de brand extension moet er een `_quarto.yml` aanwezig zijn in de hoofdidrectory. Hieronder een voorbeeld van de minimum inhoud.

```yaml
project:
  type: default

```


## Opmerkingen

voor Shiny moeten de logo's worden verplaatst naar www voor weergave.

