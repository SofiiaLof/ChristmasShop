# Rapport
##### Amanda Högfeldt

## Nyckelord och SEO
Eftersom att vår hemsida har ett tema kring julen och tomtens verkstad så valde vi att våra tre nyckelord skulle vara ”Christmas”, ”Santa Claus” och ”Gifts”. Dessa tre nyckelord finns med på varje sida för att generera bra SEO. 

Annat jag har utfört som ska generera bra SEO är att jag använt mig av korrekt HTML struktur (doctype, html, head, body, main osv). Jag har även använt mig av meta-taggar som t.ex. charset som beskriver vilka tecken som stöds samt meta-taggen viewport  som ger en responsiv sida genom att ge pixlarna samma storlek på alla skärmar.  Jag har även lagt in ett lang attribut på html-taggen som beskriver vilket språk sidan är på. Jag har också applicerat så semantisk html som det går, dock innehåller bootstrap tyvärr en del divs som är icke-semantiska html-element. Bilderna har beskrivna alt-taggar och jag använder mig av title-tag i head som också bidrar med bra SEO.


## HTTP

När jag öppnar min index.html-fil i webbläsaren sker följande via HTTP. Enligt bilden tar det ca 6,5 sekunder att ladda in allt innehåll på hemsidan. Det första som sker är att webbläsaren skickar en request (GET) till webbservern om att den vill hämta html-filen. Webbservern skickar sedan en response med innehållet som gör att vi kan se det i webbläsaren. I det här fallet har responsen status code 200 vilket innebär att det lyckades. Efter att html-filen har skickats och hämtats från webbservern så sker samma sak med de resterande filerna t.ex. css-filen, bilder och bootstrapinnehåll.


![Http_screenshot](https://user-images.githubusercontent.com/89679682/149655611-1ca173b9-9e19-461c-9a52-b8d9280d4e7c.png)

>http://127.0.0.1:5501/about-us/about-us.html

URL:en börjar med protokollet (http://) som är webbens protokoll och säger åt hur GET/Requests ska skickas. Därefter kommer min server (127.0.0.1:5501) där data kan hittas. Sedan kommer / som är en sökväg följt av about-us som är foldern där det sedan går in i /about-us.html som är html-filen där själva innehållet finns som ska hämtas till webbläsaren.


## Reflektion



[Wireframe-About us.pdf](https://github.com/SofiiaLof/HTML_CSS_projektarbete/files/7873427/Wireframe-About.us.pdf)
