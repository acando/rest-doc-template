F�r att skapa om sector alarm apiet's dokumentation, beh�ver html versionen genereras utifr�n den xmlfil d�r apiet defineras.
(Du beh�ver ha ant)
K�r f�ljande target:

ant xhtml_acando -Dapidir=sector -Dapiname=sector-app-api

s� skall det skapas om i output katalogen.

Har �ndrat lite s� att css/js resurser skapas upp lokalt s� att vi inte �r beroende av vissa filer p� n�tet.