# Описание:
"Zombie Dice" е елементарна парти игра за 2-8 играчи - в нея играчите са зомби, което иска да изяде колкото се може повече мозъци. 

# Правила:
За целта се теглят и хвърлят зарове, като играчите се опитват да избегнат символите с пушки, докато изяждат мозъците на недостатъчно бързите човеци.

Заровете - 13 на брой, са потенциалните жертви. 
Играчите предизвикат късмета си, за да се доберат до повече мозъчна тъкан, като трябва да съобразят правилния момент да спрат да хвърлят зарове преди да бъдат уцелени от пушка и ходът им да приключи.

Този, който първи събере всички 13 мозъка - печели играта.

### 1. Първоначална ръка
В началото на хода, играчът тегли 3 зара и ги хвърля.

#### 1.1. Точки
Символът с мозък е една точка накрая на хода.

#### 1.2. Повторно хвърляне
Символът със стъпките позволява да се хвърли отново този конкретен зар. 

### 1.3. Принудителен край на хода
Символите с пушка са опасни, защото когато се съберат три от тях по време на един ход, то ходът приключва и не се печелят точки. 

### 2. Допълнителни хвърляния
След като се хвърлят трите зара, играчът решава дали иска да отчете точките до момента или да предизвика късмета си, като избере три нови зара, за да ги хвърли отново.

### Общи
Целта на играта е да се съберат 13 точки и да се постигне баланс между риск и награда.

Използваните символи за страните на заровете: 🧠 - точки, 👣 - повторно хвърляне, 💥 - пушка

Заровете, от които се състои играта са 6-стенни и общо 13 на брой:

6 "зелени" - 3х🧠,2х👣,1х💥

4 "жълти" - 2х🧠, 2х👣, 2х💥

3 "червени" - 1х🧠, 2х👣, 3х💥

# Интерфейс на играта:

Играта е изцяло конзолна и всеки ход трябва да се отпечатват следните данни:

```
===
Таблица с точките всички играчи
Име на играч, който е на ход
===
Изтеглени зарове
Резултат от заровете
===
Допълнителни тегления и хвърляния*
Резултат от заровете
===
```

# Изисквания
Команда за стартиране на играта с настройка за брой и имена на играчите

Команда за повторно хвърляне

Команда за край на ход или теглене на още зарове

Автоматичен край на играта и команда за повторна игра със същите параметри

# Източници
Източник правила: [Wikipedia](https://en.wikipedia.org/wiki/Zombie_Dice)

Видео с правила: [Ozone](https://youtu.be/KwhU2PVec3k)