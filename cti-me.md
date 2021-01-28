

# Struktura
  app = střeva
  web = Složka se kterou pracuješ
  min = složka kterou dáváš na ftp.


## První kroky

  Přes příkazovou řádku se dostaň do lokace tohoto rozcestníku, kde je tento soubor.

  Poté pokrčuj příkazy níže:

  → cd app
  → npm run instalovat
  → grunt

## Druhé kroky

  Od této chvíle by se měl spustit liveserver.
  Ve složce web je web se všema souborama. Které se po uložení kompilují do složky ../min/* kde budou v minifikované a vyčištěné formě připraveny pro nahrání na FTP.
  Originální soubory zůstavají ve složce web.
  Ve složce app jsou střeva aplikace.