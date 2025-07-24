<!--
author: Volker Göhler, Niklas Werner
email: volker.goehler@informatik.tu-freiberg
version: 0.2.2
repository: https://github.com/Ifi-DiAgnostiK-Project/Holzarten
edit: true

@diagnostik_url: https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Holzarten/refs/heads/main/img

@diagnostik_image: <div class="image-container"><img src="@0/@1" alt="@1" style="height: @2rem"></div>

@style
.image-container {
  width: 200px;
  height: 200px;
  border: 1px solid #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  background-color: #f8f8f8;
}

.image-container img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}
@end



@Hoelzer1.Pappel.src: @diagnostik_url/Hoelzer1/Pappel.jpg
@Hoelzer1.Pappel: @diagnostik_image(@diagnostik_url,Hoelzer1/Pappel.jpg,@0)

@Hoelzer1.Balsa.src: @diagnostik_url/Hoelzer1/Balsa.jpg
@Hoelzer1.Balsa: @diagnostik_image(@diagnostik_url,Hoelzer1/Balsa.jpg,@0)

@Hoelzer1.Birke.src: @diagnostik_url/Hoelzer1/Birke.jpg
@Hoelzer1.Birke: @diagnostik_image(@diagnostik_url,Hoelzer1/Birke.jpg,@0)

@Hoelzer1.Laerche.src: @diagnostik_url/Hoelzer1/Laerche.jpg
@Hoelzer1.Laerche: @diagnostik_image(@diagnostik_url,Hoelzer1/Laerche.jpg,@0)

@Hoelzer1.Schwarzerle.src: @diagnostik_url/Hoelzer1/Schwarzerle.jpg
@Hoelzer1.Schwarzerle: @diagnostik_image(@diagnostik_url,Hoelzer1/Schwarzerle.jpg,@0)

@Hoelzer1.Weisstanne.src: @diagnostik_url/Hoelzer1/Weisstanne.jpg
@Hoelzer1.Weisstanne: @diagnostik_image(@diagnostik_url,Hoelzer1/Weisstanne.jpg,@0)

@Hoelzer1.Kiefer.src: @diagnostik_url/Hoelzer1/Kiefer.jpg
@Hoelzer1.Kiefer: @diagnostik_image(@diagnostik_url,Hoelzer1/Kiefer.jpg,@0)

@Hoelzer1.Ahorn.src: @diagnostik_url/Hoelzer1/Ahorn.jpg
@Hoelzer1.Ahorn: @diagnostik_image(@diagnostik_url,Hoelzer1/Ahorn.jpg,@0)

@Hoelzer1.Roteiche.src: @diagnostik_url/Hoelzer1/Roteiche.jpg
@Hoelzer1.Roteiche: @diagnostik_image(@diagnostik_url,Hoelzer1/Roteiche.jpg,@0)

@Hoelzer1.Pockholz.src: @diagnostik_url/Hoelzer1/Pockholz.jpg
@Hoelzer1.Pockholz: @diagnostik_image(@diagnostik_url,Hoelzer1/Pockholz.jpg,@0)

@Hoelzer1.Kirschbaum.src: @diagnostik_url/Hoelzer1/Kirschbaum.jpg
@Hoelzer1.Kirschbaum: @diagnostik_image(@diagnostik_url,Hoelzer1/Kirschbaum.jpg,@0)

@Hoelzer1.Buche.src: @diagnostik_url/Hoelzer1/Buche.jpg
@Hoelzer1.Buche: @diagnostik_image(@diagnostik_url,Hoelzer1/Buche.jpg,@0)

@Hoelzer1.Ulme_Ruester.src: @diagnostik_url/Hoelzer1/Ulme_Ruester.jpg
@Hoelzer1.Ulme_Ruester: @diagnostik_image(@diagnostik_url,Hoelzer1/Ulme_Ruester.jpg,@0)

@Hoelzer1.Douglasie.src: @diagnostik_url/Hoelzer1/Douglasie.jpg
@Hoelzer1.Douglasie: @diagnostik_image(@diagnostik_url,Hoelzer1/Douglasie.jpg,@0)

@Hoelzer1.Nussbaum.src: @diagnostik_url/Hoelzer1/Nussbaum.jpg
@Hoelzer1.Nussbaum: @diagnostik_image(@diagnostik_url,Hoelzer1/Nussbaum.jpg,@0)

@Hoelzer1.Linde.src: @diagnostik_url/Hoelzer1/Linde.jpg
@Hoelzer1.Linde: @diagnostik_image(@diagnostik_url,Hoelzer1/Linde.jpg,@0)

@Hoelzer1.Edelkastanie.src: @diagnostik_url/Hoelzer1/Edelkastanie.jpg
@Hoelzer1.Edelkastanie: @diagnostik_image(@diagnostik_url,Hoelzer1/Edelkastanie.jpg,@0)

@Hoelzer1.Elsbeere.src: @diagnostik_url/Hoelzer1/Elsbeere.jpg
@Hoelzer1.Elsbeere: @diagnostik_image(@diagnostik_url,Hoelzer1/Elsbeere.jpg,@0)

@Hoelzer1.Robinie.src: @diagnostik_url/Hoelzer1/Robinie.jpg
@Hoelzer1.Robinie: @diagnostik_image(@diagnostik_url,Hoelzer1/Robinie.jpg,@0)

@Hoelzer1.Esche.src: @diagnostik_url/Hoelzer1/Esche.jpg
@Hoelzer1.Esche: @diagnostik_image(@diagnostik_url,Hoelzer1/Esche.jpg,@0)

@Hoelzer1.Fichte.src: @diagnostik_url/Hoelzer1/Fichte.jpg
@Hoelzer1.Fichte: @diagnostik_image(@diagnostik_url,Hoelzer1/Fichte.jpg,@0)

@Hoelzer1.Birnbaum.src: @diagnostik_url/Hoelzer1/Birnbaum.jpg
@Hoelzer1.Birnbaum: @diagnostik_image(@diagnostik_url,Hoelzer1/Birnbaum.jpg,@0)

@Hoelzer1.Weisseiche.src: @diagnostik_url/Hoelzer1/Weisseiche.jpg
@Hoelzer1.Weisseiche: @diagnostik_image(@diagnostik_url,Hoelzer1/Weisseiche.jpg,@0)

@Hoelzer2.Laerche.src: @diagnostik_url/Hoelzer2/Laerche.jpg
@Hoelzer2.Laerche: @diagnostik_image(@diagnostik_url,Hoelzer2/Laerche.jpg,@0)

@Hoelzer2.Kiefer.src: @diagnostik_url/Hoelzer2/Kiefer.jpg
@Hoelzer2.Kiefer: @diagnostik_image(@diagnostik_url,Hoelzer2/Kiefer.jpg,@0)

@Hoelzer2.Ahorn.src: @diagnostik_url/Hoelzer2/Ahorn.jpg
@Hoelzer2.Ahorn: @diagnostik_image(@diagnostik_url,Hoelzer2/Ahorn.jpg,@0)

@Hoelzer2.Eiche2.src: @diagnostik_url/Hoelzer2/Eiche2.jpg
@Hoelzer2.Eiche2: @diagnostik_image(@diagnostik_url,Hoelzer2/Eiche2.jpg,@0)

@Hoelzer2.Mooreiche.src: @diagnostik_url/Hoelzer2/Mooreiche.jpg
@Hoelzer2.Mooreiche: @diagnostik_image(@diagnostik_url,Hoelzer2/Mooreiche.jpg,@0)

@Hoelzer2.Nussbaum.src: @diagnostik_url/Hoelzer2/Nussbaum.jpg
@Hoelzer2.Nussbaum: @diagnostik_image(@diagnostik_url,Hoelzer2/Nussbaum.jpg,@0)

@Hoelzer2.Buche2.src: @diagnostik_url/Hoelzer2/Buche2.jpg
@Hoelzer2.Buche2: @diagnostik_image(@diagnostik_url,Hoelzer2/Buche2.jpg,@0)

@Hoelzer2.Esche.src: @diagnostik_url/Hoelzer2/Esche.jpg
@Hoelzer2.Esche: @diagnostik_image(@diagnostik_url,Hoelzer2/Esche.jpg,@0)

@Hoelzer2.Kirsche.src: @diagnostik_url/Hoelzer2/Kirsche.jpg
@Hoelzer2.Kirsche: @diagnostik_image(@diagnostik_url,Hoelzer2/Kirsche.jpg,@0)

@Hoelzer2.Ahorn2.src: @diagnostik_url/Hoelzer2/Ahorn2.jpg
@Hoelzer2.Ahorn2: @diagnostik_image(@diagnostik_url,Hoelzer2/Ahorn2.jpg,@0)

@Hoelzer2.Zebrano.src: @diagnostik_url/Hoelzer2/Zebrano.jpg
@Hoelzer2.Zebrano: @diagnostik_image(@diagnostik_url,Hoelzer2/Zebrano.jpg,@0)

@Hoelzer2.Eiche.src: @diagnostik_url/Hoelzer2/Eiche.jpg
@Hoelzer2.Eiche: @diagnostik_image(@diagnostik_url,Hoelzer2/Eiche.jpg,@0)

@Hoelzer2.Mahagonie.src: @diagnostik_url/Hoelzer2/Mahagonie.jpg
@Hoelzer2.Mahagonie: @diagnostik_image(@diagnostik_url,Hoelzer2/Mahagonie.jpg,@0)

@Hoelzer2.Vogelaugenahorn.src: @diagnostik_url/Hoelzer2/Vogelaugenahorn.jpg
@Hoelzer2.Vogelaugenahorn: @diagnostik_image(@diagnostik_url,Hoelzer2/Vogelaugenahorn.jpg,@0)

-->

# Link zu LiaScript

[![LiaScript Course](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Holzarten/refs/heads/main/makros.md)

[![LiaScript LiveEditor](https://raw.githubusercontent.com/LiaScript/LiaScript/refs/heads/development/badges/editor.svg)](https://liascript.github.io/LiveEditor/?/show/file/https://raw.githubusercontent.com/Ifi-DiAgnostiK-Project/Holzarten/refs/heads/main/makros.md)



> Diese Datei ist automatisch generiert und enthält Makros für die DiAgnostiK-Holzartenbilder.

# Anleitung

> Der Befehl zum einbinden eines Bildes lautet `@<Bereich>.<Name>(Größe)`.
> Hängt man statt der Größe `.src` an den Befehl an, so wird der Link zum Bild angezeigt. `@<Bereich>.<Name>.src`
> - Der Bereich ist der Ordnername, in dem sich das Bild befindet.
> - Der Name ist der Dateiname ohne Endung.
> - Die Größe ist in Zeilen angegeben, die das Bild hoch sein soll.
Alle Bilder sowie ihre Bereiche und die Befehle um sie zu laden sind in den Tabellen weiter unten abgebildet.
**Die Anzeige benötigt LiaScript!**

## Beispiel

`@Hoelzer2.Laerche(10)`

@Hoelzer2.Laerche(10)

`@Hoelzer2.Laerche.src`

@Hoelzer2.Laerche.src

## Bereiche und Befehle

Im Nachfolgenden sind alle Bilder aller Bereiche und passende Befehle aufgelistet, die in dieser Sammlung enthalten sind.


### Hoelzer1

|Bild|Name|Befehl|
|---|---|---|
|@Hoelzer1.Pappel(10)|`Pappel.jpg`|`@Hoelzer1.Pappel(10)`|
|@Hoelzer1.Balsa(10)|`Balsa.jpg`|`@Hoelzer1.Balsa(10)`|
|@Hoelzer1.Birke(10)|`Birke.jpg`|`@Hoelzer1.Birke(10)`|
|@Hoelzer1.Laerche(10)|`Laerche.jpg`|`@Hoelzer1.Laerche(10)`|
|@Hoelzer1.Schwarzerle(10)|`Schwarzerle.jpg`|`@Hoelzer1.Schwarzerle(10)`|
|@Hoelzer1.Weisstanne(10)|`Weisstanne.jpg`|`@Hoelzer1.Weisstanne(10)`|
|@Hoelzer1.Kiefer(10)|`Kiefer.jpg`|`@Hoelzer1.Kiefer(10)`|
|@Hoelzer1.Ahorn(10)|`Ahorn.jpg`|`@Hoelzer1.Ahorn(10)`|
|@Hoelzer1.Roteiche(10)|`Roteiche.jpg`|`@Hoelzer1.Roteiche(10)`|
|@Hoelzer1.Pockholz(10)|`Pockholz.jpg`|`@Hoelzer1.Pockholz(10)`|
|@Hoelzer1.Kirschbaum(10)|`Kirschbaum.jpg`|`@Hoelzer1.Kirschbaum(10)`|
|@Hoelzer1.Buche(10)|`Buche.jpg`|`@Hoelzer1.Buche(10)`|
|@Hoelzer1.Ulme_Ruester(10)|`Ulme_Ruester.jpg`|`@Hoelzer1.Ulme_Ruester(10)`|
|@Hoelzer1.Douglasie(10)|`Douglasie.jpg`|`@Hoelzer1.Douglasie(10)`|
|@Hoelzer1.Nussbaum(10)|`Nussbaum.jpg`|`@Hoelzer1.Nussbaum(10)`|
|@Hoelzer1.Linde(10)|`Linde.jpg`|`@Hoelzer1.Linde(10)`|
|@Hoelzer1.Edelkastanie(10)|`Edelkastanie.jpg`|`@Hoelzer1.Edelkastanie(10)`|
|@Hoelzer1.Elsbeere(10)|`Elsbeere.jpg`|`@Hoelzer1.Elsbeere(10)`|
|@Hoelzer1.Robinie(10)|`Robinie.jpg`|`@Hoelzer1.Robinie(10)`|
|@Hoelzer1.Esche(10)|`Esche.jpg`|`@Hoelzer1.Esche(10)`|
|@Hoelzer1.Fichte(10)|`Fichte.jpg`|`@Hoelzer1.Fichte(10)`|
|@Hoelzer1.Birnbaum(10)|`Birnbaum.jpg`|`@Hoelzer1.Birnbaum(10)`|
|@Hoelzer1.Weisseiche(10)|`Weisseiche.jpg`|`@Hoelzer1.Weisseiche(10)`|

### Hoelzer2

|Bild|Name|Befehl|
|---|---|---|
|@Hoelzer2.Laerche(10)|`Laerche.jpg`|`@Hoelzer2.Laerche(10)`|
|@Hoelzer2.Kiefer(10)|`Kiefer.jpg`|`@Hoelzer2.Kiefer(10)`|
|@Hoelzer2.Ahorn(10)|`Ahorn.jpg`|`@Hoelzer2.Ahorn(10)`|
|@Hoelzer2.Eiche2(10)|`Eiche2.jpg`|`@Hoelzer2.Eiche2(10)`|
|@Hoelzer2.Mooreiche(10)|`Mooreiche.jpg`|`@Hoelzer2.Mooreiche(10)`|
|@Hoelzer2.Nussbaum(10)|`Nussbaum.jpg`|`@Hoelzer2.Nussbaum(10)`|
|@Hoelzer2.Buche2(10)|`Buche2.jpg`|`@Hoelzer2.Buche2(10)`|
|@Hoelzer2.Esche(10)|`Esche.jpg`|`@Hoelzer2.Esche(10)`|
|@Hoelzer2.Kirsche(10)|`Kirsche.jpg`|`@Hoelzer2.Kirsche(10)`|
|@Hoelzer2.Ahorn2(10)|`Ahorn2.jpg`|`@Hoelzer2.Ahorn2(10)`|
|@Hoelzer2.Zebrano(10)|`Zebrano.jpg`|`@Hoelzer2.Zebrano(10)`|
|@Hoelzer2.Eiche(10)|`Eiche.jpg`|`@Hoelzer2.Eiche(10)`|
|@Hoelzer2.Mahagonie(10)|`Mahagonie.jpg`|`@Hoelzer2.Mahagonie(10)`|
|@Hoelzer2.Vogelaugenahorn(10)|`Vogelaugenahorn.jpg`|`@Hoelzer2.Vogelaugenahorn(10)`|