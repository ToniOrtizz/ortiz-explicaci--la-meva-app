# ortiz-explicacio-la-meva-app
**Activitat explicacio de la meav activitat<H2>**


###step 1
Crear la carpeta: Primer de tot, creem una carpeta que es dirà <el teu Cognom>-la-meva-app (òbviament, poses el teu cognom on diu <el teu Cognom>), i després entrem dins d'aquesta carpeta.
###step2
Descarregar l’arxiu: Ens baixem un arxiu comprimit de GitHub amb tot el codi de l’app.Instal·lar unzip: Si no tens unzip instal·lat (que és el que fem servir per descomprimir coses), ho instal·lem. Fàcil.
Descomprimir l’arxiu: Descomprimim el que hem baixat i revisem que tot estigui bé, mirant els arxius que han sortit.
Anar a la carpeta correcta: Ara ens fiquem a la carpeta getting-started-master, que és on hi ha el codi que farem servir.
##step3
Veure què hi ha dins: Mirem dins la carpeta app per confirmar que hi ha l’arxiu package.json (bàsicament el que organitza tot) i dues carpetes: spec i src, que és on està tot el codi.
Crear el Dockerfile Dins la carpeta app, hem de crear un arxiu que es dirà Dockerfile. Aquest arxiu és com un manual perquè Docker sàpiga com construir l’app.
Posar coses al Dockerfile: Escrivim les instruccions dins el Dockerfile perquè Docker sàpiga què fer: quina imatge base usar, on posar els arxius, com instal·lar el que calgui i com executar l’app.
Verificar el Dockerfile: Revisem que el Dockerfile estigui ben fet i amb el nom correcte.
##step4
Crear la imatge de Docker: Fem servir Docker per crear una "imatge" (com una còpia llesta per fer servir) de l’app, i la cridem per-comencar.
Correr el contenidor: Executem el contenidor de Docker, que és bàsicament el que llança l’app, i estarà corrent al port 3000 (l’important és que ja està funcionant).
Accedir al contenidor: Si volem entrar dins del contenidor per veure què hi ha o tocar coses, fem servir una comanda que ens deixa entrar i usar la terminal des de dins.
Buscar textos que cal traduir Fem servir grep per buscar els textos en anglès que hem de canviar, com "New Item", "No items yet! Add one above!" i "Add Item".
##step4
Canviar els textos Utilitzem sed per substituir aquests textos dins dels arxius, traduint-los al català.
Pujar els canvis a Github Creem un repo privat a GitHub que es diu <el teu Cognom>-explicacio-la-meva-app, convidem un col·lega a col·laborar-hi, i escrivim tot el que hem fet en un arxiu README.md. 

