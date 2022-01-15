<h2>
Ha med Wireframen du använde för ditt ansvarsområde (png/bmp/jpg/pdf) (Mål 7)
<br><br>
<img src="Assets/blog/rapport-blog/all-wireframes-blog.png" alt="wireframes">
 </h2>
<hr>
<br><br>
<h4>
Skriv vilka nyckelord ni valde och vad du gjort för SEO på ditt ansvarsområde. (Mål 6)
 </h4>
<hr>
<h4>
Använd bilder från Inspector verktyget och förklara i grova lag hur webläsaren använder HTTP för att besöka just din hemsida. (Mål 2)
 </h4>
 
 <img src="Assets/blog/rapport-blog/rapport-http.png" alt="http-req">

clienten och servern kommunicerar via TCP/IP för att skicka data mellan varandra. Webbläsar clienten skickar ett Http-request till servern för att få tag på en kopia av hemsidan ("GET" metoden).
Om allt går som det ska (servern accepterar http-requesten) så skickar servern ett meddelande (200 OK) med innebörden att
den godkänner förfrågan. Därefter börjar servern skicka över websidans data i små-bitar i taget (data-packets)
clienten sätter därefter ihop alla bitar data till en kopia av hemsidan och visar den i browsern.

<hr>
<h4>
 Förklara varför just den URL som används i HTTP anropet ovan används. (Använd ord som: schema/protokoll, auktoritet/server/domän, sökväg/resurs) (Mål 2) </h4>

Request URL: http://127.0.0.1:5501/blog/blog-posts.html <--- Url till hemsidan som anropas i http-requesten

 <h5>Protokoll (http://</h5>
 Den första biten av url:en, http: eller https: etc, berättar vad för kommunikationsprotokoll som används (regelverk för hur clienten ska kommunicera med servern)

<h5>ip (127.0.0.1) och port (:5501)</h5>
Efter protokoll kommer ip-adressen samt en port som är till för att identifiera enheten.

<h5>resurs/path (/blog/blog-posts.html)
Visar/navigerar sökvägen bland filerna på hemsidan.

<h4>Självständigt reflektera över och kritiskt granska de valda lösningarna i projektet gällande design och wireframes, HTML, CSS, samt Bootstrap. </h4>
