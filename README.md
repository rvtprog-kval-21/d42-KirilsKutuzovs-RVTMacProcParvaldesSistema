# Rīgas Valsts Tēhnikuma mācību procesa pārvaldes sistēma

## Projekta apraksts
Šis ir PIKC "Rīgas Valsts tehnikums" kvalifikācijas darbs, mācību procesa pārvaldes sistēma priekš Rīgas Valsts Tēhnikuma. Projekta mērķis - noveidot kopēju pārvaldes sistēmu, kas ir ieslodzīta speciāli priekš RVT, ar sekojošo funkcionalitati: 
+ Skolnieku, priekšmetu, skolotāju un klašu sarakstu pārziņa.
+ Saraksta salikšana klasēm un skolotājiem.
+ Svarīgus notikumos, tadus kā skolnieku izņēmums un pārvedums, skolotāju paņēmiens uz darbu, mācību stundu grāmatošana un t.t., registrācija ar dokumentiem.
+ Svarīgas informācijas saņemšana un analīze, tādu kā novērtējumi, apciemojumi, vidēju balli u t.t.
+ Stipendijas aprēķins

Funkcionalitāte būs sadalīta pa lomām.

## Izmantotās tehnoloģijas
Projektā tiek izmantots:
+ "**1C:Uzņēmums**" tehnoloģiska platforma  
  + 1C Programmēšanas valoda
  + 1С Pieprasījumu valoda
  + 1С Datu izkārtojuma sistēma
+ MySQL  

Svarīgs precizēt, kas "**1C:Uzņēmums**" tehnoloģiska platforma ir sarežģītā daudzlīmeņu objektu sistēma ar plašu funkcionalitati, kas orientējas uz darbu ar datubāzem un esoša iebūvēts lietotāja interfeisa mehānisms, tāpēc izmantotās tehnoloģijas saraksts ir mazs. 

## Izmantotie avoti
+ Dokumentācija un instrukcijas pa darbu ar visām 1C sistēmām:
  + [Programmist1s.ru](https://programmist1s.ru/programmirovanie-1s/)
  + [helpme1c.ru](https://helpme1c.ru/)
  + [1c-programmer-blog.ru](https://1c-programmer-blog.ru/)
+ [MySQL](https://dev.mysql.com/) - visa vajadzīga informācija par dārbu ar MySQL

## Uzstādīšanas instrukcijas
Nepieciešamas programmas un platformas:
+ **1C:Uzņēmums 8.3** tievs/resns klients, failu/klient-servera sistēma, pilna vai mēģinājuma versija. [Platformas instalēšanas instrukcija](https://programmist1s.ru/kak-ustanovit-1s-buhgalteriyu-i-drugie-konfiguratsii-kak-postavit-1s/)
+ Mana kondigurācija "RVTMacProcParvaldesSistema.cf" vai informatīva bāze "RVTMacProcParvaldesSistema.dt"

Instrukcija:
+ Atvērt 1C:Uzņemums
+ Uzspiest uz spiedpogu "Добавить"
+ Izvelēt "Создание новой информационной базы"
+ Izvelēt "Создание информационной базы без конфигурации"
+ Uzrakstit vajadzigo nosaukumu un izvelēt "На данном компьютере"
+ Norādīt vēlamo katalogu un izvēlēt valodu
+ Uzspiest uz spiedpogu "Готово"
+ Palaist informatīvu bāzi ar spiedpogas "Конфигуратор" palīdzību
+ "Конфигурация" -> "Открыть конфигурацию"
+ "Администрирование" -> "Загрузить информационную базу" un izvelēt failu RVTMacProcParvaldesSistema.dt
