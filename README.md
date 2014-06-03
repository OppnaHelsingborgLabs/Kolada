Kolada
======
Visar exempeldata från [Kommun- och landstingsdatabasen Kolada](http://kolada.se/) om en kommun eller ett landsting. Förhoppningen är att fler ska få upp ögonen för den rika data som Kolada har om alla Svenska kommuner och landsting. Utvecklad med Bootstrap, jQuery, Google Chart och [Koladas API](http://kolada.se/portal.php?page=index/api). Se hur det används på [oppna.helsingborg.se/kolada/](https://oppna.helsingborg.se/kolada/). 

För att visa andra nyckeltal än de som anges i kolada.js så hitta id/beskrivning på dessa nyckeltal i [Kolada](http://kolada.se/index.php?page=workspace/nt) och ändra/utöka metrics arrayen i kolada.js. För att ändra vilken kommun/landsting som ska användas så redigera muncipality och municipality_name i samma fil.

Observera att det saknas en del felhantering, tex när Koladas API inte svarar.
