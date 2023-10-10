**Celem projektu jest dokładne odwzorowanie tekstu polskiego
przekładu Biblii Świętej z 1632 roku (zarówno wydania pierwszego,
jak i wydania z 1879 roku) po to, aby tekst ten mógł posłużyć
za źródło do kolejnych publikacji oraz rewizji.**

### Kolejność zadań
>1. Pierwszym zadaniem jest korekta istniejącego już
cyfrowego tekstu wydania z 1879 roku.
<br>Skan: [1879](https://archive.org/details/biblijawietatoje00wars/page/n7/mode/2up?view=theater)
<br>Zrobione: każda księga została przynajmniej raz sprawdzona.

2. Drugim zadaniem jest odwzorowanie tekstu wydania z 1632 roku.
Wybraną metodą jest wykorzystanie do tego celu poprawionego
już tekstu wydania z 1879 roku, automatycznie zamieniając w plikach
pisownię z zastanej na siedemnastowieczną, a następnie porównanie
tekstu werset po wersecie ze skanem oryginału i naniesienie napotkanych różnic.
	- Skany:
	<br>[1632](https://drive.google.com/file/d/1MLVMZMDLZgNnFCoV1l6hrlajAzMLP9-E)
	<br>[1660](https://books.google.pl/books?id=FSZfAAAAcAAJ&dq=pismo%20%C5%9Bwi%C4%99te%201660&hl=pl&pg=RA2-PA256#v=onepage&q&f=false)
	- Instrukcje szczegółowe:
		- **Kursywa**
		<br>Tekst pochylony można oznaczyć tagiem html &lt;i&gt;&lt;/i&gt;.
		>ćiemność &lt;i&gt;<i>byłá</i>&lt;/i&gt; nád przepáśćią
 		- **Literówki**
		<br>Wydanie z 1632 roku, tak jak każda książka, posiada literówki, których powielać
		nie chcemy. Ponieważ XVII-wieczna pisownia jest nieco różna od dzisiejszej,
		w przypadku wątpliwości zalecane jest sprawdzenie pisowni w wydaniu z 1660.
		- **Odnośniki a, b, c...**
		<br>Odnośniki do przypisów pomijamy.
		- **Wielkie litery**
		<br>W użytej do wydania w 1632 roku czcionce wielkie litery nie mają kropek,
		tzn. że „Ż” będzie zapisane jako „Z”, a akapity ze względów estetycznych mają wielkie dwie
		pierwsze litery. Akapit zaczynający się więc: „ZYł” należy zapisać: „Żył” _(1Moj.5,18)._
		- **á**
		<br>Wszystkie „a” zostały automatycznie zamienione na „á”, ponieważ „á” występuje
		częściej i łatwiej jest ręczne przywrócić „a” aniżeli odwrotnie.
		- **ó**
		<br>Na tym etapie „ó ”nie jest zamieniane na „o”, aby nie tracić informacji
		potrzebnej do późniejszej aktualizacji pisowni.
		- **ſ**
		<br>Wszystkie „s” zostały automatycznie zamienione na „ſ”, ponieważ „ſ” występuje
		zdecydowanie częściej i łatwiej jest ręcznie przywrócić „s”.
		- **sz**
		<br>Dwuznak „sz” został zamieniony na „ƺ”.

### Struktura
Tekst Pisma podzielony jest na foldery odpowiadające księgom Biblii,
wewnątrz których znajdują się pliki tekstowe odpowiadające rozdziałom,
w których każda linijka odpowiada danemu wersetowi.


### Procedura nanoszenia korekt
Zmiany wprowadzać można przez interface github.com:
https://github.com/piotrskurzynski/biblia

1. Wybór odpowiedniej księgi i rozdziału
_(np. dla Rzym.5 '1879/45-rom/05.txt');_

2. Włączenie edycji 'Edit this file'
_(przy ikonie ołówka w prawym górnym rogu okna tekstu);_

3. Zatwierdzenie proponowanej zmiany 'Propose changes'
jako tytuł zmiany podając odnośnik korygowanego fragmentu
_(np. Rzym.5,8.);_

4. 'Create pull request'.


### Postęp prac
W pliku [status](/status) prowadzony jest zapis tego,
kto, które rozdziały, jakich ksiąg sprawdził.


W przypadku niechęci to zastosowanej technologii sugestie korekt
można też nadsyłać drogą mailową na adres: info@bojwiary.pl
uprasza się jednak o wcześniejsze sprawdzenie, czy sugerowane
zmiany nie zostały już tu naniesione.
