---
title: About
permalink: /about/
visitedCountries:
    - name: Ägypten
      code: EG
    - name: Belize
      code: BZ
      link: /belize/
    - name: Belgien
      code: BE
      link: /photography/benelux-2010/
    - name: Dänemark
      code: DK
    - name: Deutschland
      code: DE
      link: /deutschland/
    - name: England
      code: GB
    - name: Finnland
      code: FI
    - name: Frankreich
      code: FR
      link: /photography/paris-2019/
    - name: Georgien
      code: GE
      link: /georgien/
    - name: Griechenland
      code: GR
      link: /photography/kreta-2016/
    - name: Holland
      code: NL
      link: /photography/benelux-2010/
    - name: Indien
      code: IN
      link: /indien/
    - name: Irland
      code: IE
      link: /irland/
    - name: Island
      code: IS
      link: /island/
    - name: Israel
      code: IL
      link: /israel/
    - name: Italien
      code: IT
      link: /photography/rom-2016/
    - name: Japan
      code: JP
      link: /japan/
    - name: Jordanien
      code: JO
      link: /jordanien/
    - name: Kosovo
      code: XK
      link: /photography/suedosteuropa-2013/
    - name: Laos
      code: LA
      link: /laos/
    - name: Lettland
      code: LV
    - name: Luxemburg
      code: LU
      link: /photography/benelux-2010/
    - name: Marokko
      code: MA
      link: /marokko/
    - name: Mazedonien
      code: MK
    - name: Nepal
      code: NP
      link: /nepal/
    - name: Norwegen
      code: "NO"
      link: /photography/suedosteuropa-2013/
    - name: Palistina
      code: PS
    - name: Polen
      code: PL
    - name: Rumänien
      code: RO
      link: /rumaenien/
    - name: Schottland
      link: /schottland/
    - name: Schweden
      code: SE
      link: /photography/schweden-2010/
    - name: Schweiz
      code: CH
    - name: Serbien
      code: RS
      link: /photography/suedosteuropa-2013/
    - name: Spanien
      code: ES
    - name: Sri Lanka
      code: LK
      link: /sri-lanka/
    - name: Thailand
      code: TH
      link: /thailand/
    - name: Türkei
      code: TR
      link: /photography/tuerkei-2014/
    - name: Vatikan
      link: /photography/rom-2016/
    - name: Vereinigte Arabische Emirate
      code: AE
      link: /photography/abu-dhabi-2014/
    - name: Vietnam
      code: VN
      link: /vietnam/
    - name: Zypern
      code: CY
      link: /photography/zypern-2015/
---

![image-left](/assets/images/2013-08-17_Rumaenien_mit_Johannes_032.jpg){: .align-left}
Hi, ich bin Johannes. Weltenbummler, Hobbyfotograf und Technikfreak.

Auf dieser privaten Homepage möchte ich dir Bilder von meinen Reisen zeigen, sowie über Fotografie, 
Technologie, Gadgets und natürlich meine Abenteuer schreiben.

Folge mir auch gerne auf [Instagram](https://www.instagram.com/gamue16/), um auf dem Laufenden zu bleiben. 
Denn dort poste ich während meinen Reisen entsprechende Stories, noch bevor ich die Homepage entsprechend aktualisiere.

## Folgende {{ page.visitedCountries.size }} Länder habe ich schon bereist:

{% include custom/visited-countries.html countries=page.visitedCountries %}

<ul class="countries">
{% for country in page.visitedCountries %}
    <li>
    {% if country.link %}
    <a href="{{ country.link }}">{{ country.name }}</a>
    {% else %}
    {{ country.name }}
    {% endif %}
    </li>
{% endfor %}
</ul>

## Kontakt

Wenn du Fragen zu meinen Reisen oder einem Beitrag hast, schreib gerne einen Kommentar auf der jeweiligen Seite, 
kontaktiere mich über das [Kontaktformular](/contact/) oder Social Media.

## Die längere Version

Ich bin in einem beschaulichen Dorf zwischen Karlsruhe und Stuttgart aufgewachsen und hatte schon immer 
ein Faibel für Computer, Technik und Fotografie. Das mit dem Reisen kam erst als ich 2009 meine 
Ausbildung zum Informatikkaufmann beendet hatte und zusammen mit einem Freund nach Irland aufgebrochen bin, 
um das Land mit einem Mietwagen zu erkunden.

Einige Monate später folgte mein erster Solo-Backpacking-Trip nach Israel, bei dem ich eine mir fremde Kultur entdecken, 
viele interessante Menschen kennenlernen und faszinierende Natur oder Bauwerke bewundern durfte. 
Was in mir den Appetit auf mehr geweckt hat. Seitdem habe ich massenhaft Flugmeilen und Stempel im Reisepass gesammelt. 
Wanderte durch etliche Wüsten, bin über den Jordan gegangen, hab den Himalaja bewundert, 
trieb im Toten Meer oder planschte in Islands heißen Quellen. Immer auf der Jagd nach neuen Abenteuern und Erfahrungen.

Auf den Reisen hatte ich natürlich immer meine Kamera im Gepäck, sodass dabei etliche Bilder entstanden sind und 
ich so Freunde und Familie an meinen Erfahrungen und Erlebnissen teilhaben lassen konnte. 
Durch meine Technik- und Internetaffinität kam ich auf die Idee damit eine Homepage zu erstellen, wodurch dann schließlich diese Seite entstanden ist. 

Zu Beginn habe ich noch häufiger Reiseberichte geschrieben, habe das aber irgendwann zeitlich nicht mehr hinbekommen bzw. 
die Muse gehabt diese zu verfassen. Solltet ihr aber Fragen zu einer Tour oder einem Reiseland haben, 
meldet euch einfach bei mir ;). 

Seit der [Umstellung der Seite auf Jekyll]({% post_url 2019-09-01-relaunch %}) gelingt es mir auch wieder regelmäßiger Updates zu posten 
oder Informationen rund um die Reiserouten und Stationen zu veröffentlichen. 
Abgesehen von Reiseberichten und -tipps schreibe ich auch über Fotografie- und Technikthemen, 
an denen ich gerade arbeite oder die mich beschäftigen. Denn in gewisser Weise ist die Homepage auch eine Experimentier- 
und Lernplattform für mich um neue Technologien oder Programmiersprachen auszuprobieren, deren Ergebnisse ich ebenfalls gerne teile.
