F�r att skapa om sector alarm apiet's dokumentation, beh�ver html versionen genereras utifr�n den xmlfil d�r apiet defineras.

(Du beh�ver ha ant)

K�r f�ljande target:

ant xhtml_acando -Dapidir=..\sector-alarm\doc\api -Dapiname=sector-app-api -Dtargetdir=..\sector-alarm\doc\api

(apidir & targetdir b�r peka p� api dokumentationens katalog i sector-alarm git hub projektet)

s� skall det skapas om i output katalogen.

Har �ndrat lite s� att css/js resurser skapas upp lokalt s� att vi inte �r beroende av vissa filer p� n�tet.