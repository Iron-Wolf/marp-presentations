---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
---

# Demoscene
<!-- tests avec des images random -->
![bg left:60%](https://i.ytimg.com/vi/JZ6ZzJeWgpY/maxresdefault.jpg)
![bg](https://pbs.twimg.com/media/GKO2i_uXUAAsCRI?format=jpg)
![bg](https://i.ytimg.com/vi/t6jlhqNxRYk/maxresdefault.jpg)

---

# Définitions
- **Demoscene :** réseau de créateurs ayant pour but de faire de l'art sous forme de programme informatique, appelé **démos** 
- **Démo :** clip musical généré par ordinateur démontrant quels effets graphiques et sonores peuvent être réalisés en utilisant le hardware à son plein potentiel
- **Démoparty :** événement rassemblant les artistes de la scène, pour confronter leurs créations (les plus importantes ont des remises de prix)

<!-- source : 
https://www.demoscene.info/index.html 
-->

---
# Historique - 1980
- Emergence de la scène grâce à l'essor des PC (copyparty)
- Echanges de logiciel cracké, souvent avec des animations (intro)

<p style="margin-left:50px;">
  <img width="400" height="300" style="float:left;"
    src="http://edu.derfunke.net/user/pages/05.DATA/03.assignment-book/18.free-haven/02.demoscene/media/adam2.jpg"></img>
  <iframe width="400" height="300" style="float:left;"
    src="https://www.youtube.com/embed/L1VF-Desm-c?mute=1" ></iframe>
</p>
<!-- source : 
http://edu.derfunke.net/data/assignment-book/free-haven/demoscene
https://demoscene-the-art-of-coding.net/2020/04/15/breakthrough-finland-accepts-demoscene-on-their-national-list-of-intangible-cultural-heritage-of-humanity/
-->

---

# Historique - 1990
- Premières démoparty
- Rassemblements "officiel", qui entrainent l'interdiction des activités illégales
- les démos deviennent purement artistique

![bg right:40%](https://upload.wikimedia.org/wikipedia/commons/e/ea/Assembly2004-areena01.jpg)

---

# Comparaison (Amiga 500)
<p style="margin-left:50px;">
  <iframe width="400" height="300" style="float:left;"
    src="https://www.youtube.com/embed/iGpU3DicbLQ?start=155&mute=1"></iframe>
  <iframe width="400" height="300" style="float:left;"
    src="https://www.youtube.com/embed/iw17c70uJes?start=270&mute=1"></iframe>
  <iframe width="400" height="200" 
    src="https://www.youtube.com/embed/eQyNJfHNleI?start=303"></iframe>
</p>

<!--On est pas la pour les ça, mais si jamais :
PC : Amiga 500 (bestselling)
Sortie : 1987
Résolution : 640×512 (PAL)
CPU : ~7 Mhz
RAM : 1MB (138 MB max)
-->


<!--
---

Je laisse la pour tester, mais pas sûr de le garder
<div style="overflow:hidden; margin: 15px auto;">
  <iframe scrolling="no" src="https://amiga.oszx.co/" 
    style="margin-left: -15px; height: 900px; margin-top: -280px; width: 780px;">
  </iframe>
</div>
-->

---

# Démo récentes

Executables de 64ko pour Windows

<iframe width="500" height="400" src="https://www.youtube.com/embed/O3T1-nadehU?mute=1" style="float:left;"></iframe>

<iframe width="500" height="400" src="https://www.youtube.com/embed/R-4wHUw_OdE?Pmute=1" style="float:left;"></iframe>

---

# Autres formes

Des vrais bouts de Ray tracer dans mon MySQL
![w:800px](https://camo.githubusercontent.com/b8c405b21dd44e60153173c12718d584aa70bd0fdde3b89fbe9b991c341ca5c9/68747470733a2f2f6d656469612e64656d6f7a6f6f2e6f72672f73637265656e732f6f2f32322f30372f303666302e3139343439342e706e67)

---

## Une demo ... jouable ?

**.kkrieger** (2004)

Executable de 96ko pour windows 

<iframe width="500" height="300" src="https://www.youtube.com/embed/2NBG-sKFaB0?mute=1" style="float:left;"></iframe>

---

## Le donut

<br/>
<iframe width="500" height="400" src="https://donut.surge.sh/"></iframe>

---

Le code du dobut

```
             k;double sin()
         ,cos();main(){float A=
       0,B=0,i,j,z[1760];char b[
     1760];printf("\x1b[2J");for(;;
  ){memset(b,32,1760);memset(z,0,7040)
  ;for(j=0;6.28>j;j+=0.07)for(i=0;6.28
 >i;i+=0.02){float c=sin(i),d=cos(j),e=
 sin(A),f=sin(j),g=cos(A),h=d+2,D=1/(c*
 h*e+f*g+5),l=cos      (i),m=cos(B),n=s\
in(B),t=c*h*g-f*        e;int x=40+30*D*
(l*h*m-t*n),y=            12+15*D*(l*h*n
+t*m),o=x+80*y,          N=8*((f*e-c*d*g
 )*m-c*d*e-f*g-l        *d*n);if(22>y&&
 y>0&&x>0&&80>x&&D>z[o]){z[o]=D;;;b[o]=
 ".,-~:;=!*#$@"[N>0?N:0];}}/*#****!!-*/
  printf("\x1b[H");for(k=0;1761>k;k++)
   putchar(k%80?b[k]:10);A+=0.04;B+=
     0.02;}}/*****####*******!!=;:~
       ~::==!!!**********!!!==::-
         .,~~;;;========;;;:~-.
             ..,--------,*/
```

---

# Ressources
Télécharger/regarder :
- http://pouet.net/
- https://curio.scene.org/
- https://www.youtube.com/watch?v=5MexnBunH_g
Tutoriels :
- https://github.com/psenough/teach_yourself_demoscene_in_14_days
- https://demobasics.pixienop.net/

<!--
article au pif que j'ai trouvé : https://nickm.com/post/tag/demoscene/
-->

---

# Merci pour votre écoute !
