# lp

> Print bestanden.
> Meer informatie: <https://manned.org/lp>.

- Toon de output van een commando met de standaard printer (bekijk het `lpstat` commando):

`echo "test" | lp`

- Toon een bestand met de standaard printer:

`lp {{pad/naar/bestandsnaam}}`

- Toon een bestand met een printer met naam (bekijk het `lpstat` commando):

`lp -d {{printer_naam}} {{pad/naar/bestandsnaam}}`

- Toon N kopieën van een bestand met de standaard printer (vervang N met het gewenste aantal kopieën):

`lp -n {{N}} {{pad/naar/bestandsnaam}}`

- Toon alleen specifieke pagina's met de standaard printer (print pagina's 1, 3-5, and 16):

`lp -P 1,3-5,16 {{pad/naar/bestandsnaam}}`

- Hervat het printen van een taak:

`lp -i {{taak_id}} -H resume`
