# rm

> Verwijder bestanden of directories.
> Bekijk ook: `rmdir`.
> Meer informatie: <https://www.gnu.org/software/coreutils/manual/html_node/rm-invocation.html>.

- Verwijder specifieke bestanden:

`rm {{pad/naar/bestand1 pad/naar/bestand2 ...}}`

- Verwijder specifieke bestanden waarbij niet-bestaande genegeerd worden:

`rm {{[-f|--force]}} {{pad/naar/bestand1 pad/naar/bestand2 ...}}`

- Verwijder specifieke bestanden interactief met een prompt voor elke verwijdering:

`rm {{[-i|--interactive]}} {{pad/naar/bestand1 pad/naar/bestand2 ...}}`

- Verwijder specifieke bestanden met het afdrukken van informatie over elke verwijdering:

`rm {{[-v|--verbose]}} {{pad/naar/bestand1 pad/naar/bestand2 ...}}`

- Verwijder specifieke bestanden en directories recursief:

`rm {{[-r|--recursive]}} {{pad/naar/bestand_of_map1 pad/naar/bestand_of_map2 ...}}`

- Verwijder lege directories (dit wordt beschouwd als de veilige methode):

`rm {{[-d|--dir]}} {{pad/naar/map}}`
