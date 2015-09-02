# Dagbog  #

1. Installation af Postgres.<br>o Installationssæt hentes fra [http://www.enterprisedb.com/products-services-training/pgdownload](http://www.enterprisedb.com/products-services-training/pgdownload), Windows Ver. 9.4.4 - 64 bit.<br>o Efter hovedinstallation af PostgreSQL installeres PostGIS 2.1 - 64 bit vha "Application Stack Builder"

2. Opsætning af parametre til postgres.<br>PostgreSQL opsætning skal "tunes" for at fungere OK på den valgte server; se f.eks.: [http://pgtune.leopard.in.ua/](http://pgtune.leopard.in.ua/) 

3. Oprettelse af database vejbelysning<br>Oprettes vha prgram "PG Admin III" installeret sammen med databaseserver.<br>o Højreklik på "Databases" i "Object browser", menupunkt "New database" og udfyld feltet
4. Oprettelse af extension "PostGIS" til database "vejbelysning"<br>I PG Admin III, browses til database 
5. Oprettelse af schema "raadata"