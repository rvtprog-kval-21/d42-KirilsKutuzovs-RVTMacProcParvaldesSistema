# Rīgas Valsts Tēhnikuma mācību procesa pārvaldes sistēma

## Projekta apraksts
Šis ir PIKC "Rīgas Valsts tehnikums" kvalifikācijas darbs, mācību procesa pārvaldes sistēma priekš Rīgas Valsts Tēhnikuma. Projekta mērķis - noveidot kopēju pārvaldes sistēmu, kas ir ieslodzīta speciāli priekš RVT, ar sekojošo funkcionalitati: 
+ Skolnieku, priekšmetu, skolotāju un klašu sarakstu pārziņa.
+ Saraksta salikšana.
+ Svarīgus notikumos, tadus kā skolnieku izņēmums un pārvedums, skolotāju un citu darbnieku paņēmiens uz darbu/atlaišana, mācību stundu grāmatošana un t.t., registrācija ar dokumentiem.
+ Svarīgas informācijas saņemšana un analīze, tādu kā novērtējumi, apciemojumi, vidēju balli u t.t.
+ Stipendijas aprēķins

Funkcionalitāte būs sadalīta pa lomām.

## Izmantotās tehnoloģijas
Projektā tiek izmantots:
+ "**1C:Uzņēmums**" tehnoloģiska platforma  
  + 1C Programmēšanas valoda
  + 1С Pieprasījumu valoda
  + 1С Datu izkārtojuma sistēma  

Svarīgs precizēt, kas "**1C:Uzņēmums**" tehnoloģiska platforma ir sarežģītā daudzlīmeņu objektu sistēma ar plašu funkcionalitati, kas orientējas uz darbu ar datubāzem un esoša iebūvēts lietotāja interfeisa mehānisms, tāpēc izmantotās tehnoloģijas saraksts ir mazs. 

## Izmantotie avoti
+ Dokumentācija un instrukcijas pa darbu ar visām 1C sistēmām:
  + [Programmist1s.ru](https://programmist1s.ru/programmirovanie-1s/)
  + [helpme1c.ru](https://helpme1c.ru/)
  + [1c-programmer-blog.ru](https://1c-programmer-blog.ru/)
+ https://moluch.ru/archive/291/66058/
+	https://habr.com/ru/post/193136/

## Uzstādīšanas instrukcijas
+ Nepieciešama programatura:
  + Ieejiet uz saitu https://online.1c.ru/catalog/free/28765768/;
  + Izvēlaties "Получить продукт бесплатно", aizpildiet anketu, obligāti ievediet stradajoso E-mail, fails bus sutits uz vinu;
  + Piekraujiet arhīvu, izsaiņojiet, palaidiet Setup.exe;
  + Uzstādīšanas uzskaņošanās, nodalījumā "Интерфейсы на различных языках" atrodiet "Латышский" un izvelaties "Данный компонент будет установлен на локальтый жесткий диск".
  + Nākamajā nodalījumā izvelaties "Латышский", pavadiet uzstādīšanu
+ Informatīvas bāzes uzstādīšana:
  + Jums ir nepieciesams noladiet manu informacijas bazi failu (RVTMacProcParvaldesSistema.dt)
  + Palaidiet „1C:Uzņemums”;
  + Pie pirmās „1C:Uzņemums” jums piedāvās veidot jaunu informatīvu bāzi, piekrītiet. Ja nepiedāvājuši, uzspiediet uz "Pievienot";
  + Izvelaties "Izveidot jaunu informacijas bazi", izvēlaties "Izveidot informacijas bazi bez konfiguracijas";
  + Varat izvēlēties jebkādu nosaukumu un informacijas bazes katalogu, izvēlaties latviesu (latvija) valodu;
  + Pārējas uzskaņošanas nemainām un izvelam "Gatavs";
  + Palaidiet informatīvu bāzi režīmā "Konfigurators";
  + Administresana -> Ieladet informacijas bazi... -> izvelam noladito failu (RVTMacProcParvaldesSistema).
+ Programmas palaišana:
  + Palaidiet „1C:Uzņemums”;
  + Izvelaties atbilstošu informatīvu bāzi un palaidiet režīmā "1C:Uzņemums ".
 


