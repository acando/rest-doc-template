För att skapa om sector alarm apiet's dokumentation, behöver html versionen genereras utifrån den xmlfil där apiet defineras.

(Du behöver ha ant)

Kör följande target:

ant xhtml_acando -Dapidir=..\sector-alarm\doc\api -Dapiname=sector-app-api -Dtargetdir=..\sector-alarm\doc\api

(apidir & targetdir bör peka på api dokumentationens katalog i sector-alarm git hub projektet)

så skall det skapas om i output katalogen.

Har ändrat lite så att css/js resurser skapas upp lokalt så att vi inte är beroende av vissa filer på nätet.