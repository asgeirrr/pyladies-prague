# Zkušenosti z prvního běhu PyLadies v Praze

## Úvod

První běh PyLadies v Praze byl poměrně úspěšný, ale nebyl bez problémů. Proto bych v tomto dokumentu rád shromáždil zkušenosti z celého běhu od všech, kteří k tomu mají co říct -- tedy od studentek i koučů -- aby příští běh proběhl lépe. Pro přehlednost bych chtěl problémy rozdělit do několika kategorií -- Organizace a komunikace, Technické problémy a Výuka.

## 1. Organizace a komunikace

### 1.1 Zdůraznit práci na úkolech
Od začátku bychom měli říkat, že kurz vyžaduje důslednou práci na úkolech, bez nich je kurz méně než polovičatý. Zároveň ale nabízet pomoc při jejich plnění (individuální či hromadné konzultace, popř. pomoc online) a nabádat k jejímu využití.

### 1.2 Dát najevo, že jsme všichni začínali stejně
Bylo vidět, že holky si často připadaly ztraceně nebo hloupě. Ty pocity zažívají i zkušení programátoři každý den, ale to začátečník neví a připadá si, že se nikdy nemůže naučit programovat. Pomohlo by, kdyby kouči zdůrazňovali, že začátky jsou těžké, a u náročnější partie explicitně říct něco jako: "Já tohle pochopil až napočtvrté/po měsíci." nebo "Tohle téma se na VŠ bere půl semestru."

### 1.3 Poučit dopředu všechny kouče o desateru
V průběhu jsme zjistili, že i když si všichni přejeme přátelskou atmosféru, nemůže být na srazech chaos. Terka proto dala dohromady [Desatero pro kouče](https://github.com/PyLadiesCZ/pyladies/issues/15). Důležité je hlavně nedělat práci za holky, pomáhat jim, ale nechat je na řešení přijít samy. Pak taky zajistit hlavnímu koučovi klid na práci a to jak ze strany vedlejších koučů, tak ze strany studentek.

### 1.4 Držet počet hlavních koučů v rozumných mezích
Přílišné střídání koučů není pro kurz dobré. Podmínka, aby hlavní kouč byl alespoň vedlejším koučem na předešlém srazu je nutná. Ale i tak by bylo lepší držet počet hlavních koučů nízký (řekněme do 4) a nestřídat je často, spíš se snažit naplánovat pro hlavního kouče blok 3 nebo 4 srazů po sobě. Střídání po jedné hodině je náročné pro hlavního kouče i pro holky.

### 1.5 Psát shrnutí
Červené a zelené papírky jsou hezký suvenýr pro hlavního kouče, ale zvlášť když se hlavních koučů střídá víc, měly by připomínky být dostupné všem. Bylo by fajn, kdyby hlavní kouč vždycky napsal krátké shrnutí. ([příklad](https://github.com/PyLadiesCZ/pyladies/blob/gh-pages/v1/s004-strings/poznamky.txt))

## 2. Technické problémy

### 2.1 Vyzkoušet materiály pro všechny platformy
Nejčastěji byl problém s Windows, někdy s MacOS (viz Grafika na Verčině MacBooku). Hlavní kouč musí mít v Windows v malíčku -- instalaci Pythonu, Unicode znaky, nepoužitelný terminál a práci s Gitem (hlavně kterou instalačku použít).

Tyto problémy by měly být zmíněny i v materiálech. (V Brně je nedostatek Windowsích koučů, tak se řešení bastlí na srazu na koleně, a výsledky tohohle jsem do materiálů pak radši nedal – PV)

### 2.2 Dělat úlohy maximálně multiplatformní
Různé instrukce pro různé systémy jsou pro holky zbytečně matoucí a hlavnímu koučovi ubírají čas na vysvětlení samotného problému. Do příštího kurzu by bylo dobré zvážit použití [Minicondy](http://conda.pydata.org/miniconda.html) a [IPython](http://ipython.org/) Notebooku, což jsou nástroje, které se chovají na všech platformách stejně (teoreticky) a na Windows řadu věcí zjednodušují (hlavně instalaci knihoven jako je NumPy či SciPy, které mohou být snadno použity pro zpestření úkolů). Instrukce by pak mohly být pro různé platformy podobnější.

[Pozn. PV] V mém podání má kurz učit i práci s příkazovou řádkou a Gitem, bez kterých se programátor neobejde. Takže Notebook leda na nějaké odbočky (viz Data). Minicondě bych se v zásadě nebránil, (zvlášť pokud by byla použitá jen pro Windows) – pokud pod ní teda funguje pip.

## 3. Výuka

### 3.1 Nebrat harmonogram závazně
Harmonogram je potřeba, ale není to tak, že by přes něj nějel vlak. Každá skupina bude jiná a bude postupovat jiným tempem popř. jí půjdou různá témata různě rychle. Myslím, že jsme se všichni cítili zavázáni harmonogramem hlavně kvůli tomu, že Petr Viktorin připravil výborné materiály a my chtěli postupovat podle nich. A to přesto, že jsme viděli, jak jsme holky na začátku dost zavalili. Je potřeba na začátku nepodcenit představování a zjistit, jaké mají holky zkušenosti a jaké jsou jejich cíle a podle toho přizpůsobit harmonogram.

### 3.2 Nekompromisně vyžadovat úkoly
Úkolů bylo hodně a holky je vůbec nestíhaly a zdálo se, že jejich objem je dost děsí. Možná jich není potřeba tolik. Kdyby holky udělaly jen polovinu, pořád by si asi dané téma dost procvičilo. Ale je nutné je udělat, tím se osamostatní při programování od koučů.

Objevil se nápad, aby kromě výkladu byla další hodina vyloženě konzultace nad úkoly, popř. jeden týden učit, druhý týden konzultovat. 

[Pozn. PV] Nové úkoly mají od [druhé sady](http://pyladies.cz/v1/s002-hello-world/handout/handout2.pdf) sekce s poznámkou, co se v nich dělá a jak je to důležité. Snad tenhle experiment vyjde.

### 3.3 Prakticky zaměřené úlohy

Téma srazu může být např. _Seznamy_, ale výstupem by mělo být něco užitečného, při čem se seznamy procvičí, a zároveň by to mělo mít nějaký pěkný výstup (např. graf nebo jinou vizualizaci), tím podpoříme radost z programování. Není dobré vyjmenovávat všechno, co se dá se seznamy dělat, spíš se soustředit na základní použití. Poskytnutí [taháku](http://pyladies.cz/v1/s007-cards/list-cheatsheet.html) všech funkcí seznamů je ale užitečné.

### 3.4 Vyvarovat se příliš komplexním úlohám
Obtížnějších úloh jako byl např. Solitaire bychom se měli vyvarovat. V základním kurzu by mělo být cílem naučit holky formalizovat drobný problém z reálného světa a implementovat ho v Pythonu. Přínosnější je dělat více menších úloh než jednu velkou, ve které se budou holky ztrácet.
