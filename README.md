# 3D Слънчева система
Разработчик: Даниел Милев <br>

<<<<<<< HEAD
Автор: Даниел Милев <br>

=======
>>>>>>> 41205a069236c262808840261ba591ee1ec0ab7a
<a href="https://github.com/danitmb/SolarSystem/raw/refs/heads/main/install/SolarSystem.zip">Свали</a>

# Въведение

Проектът има за цел да разработи 3D симулация на Слънчевата система, използвайки OpenGL и съвременни мултимедийни технологии. Тази симулация ще улесни изучаването на геометрията, позициите и орбиталните скорости на планетите и техните луни. Освен това, тя предлага общ преглед на астероидния пояс, разположен между Марс и Юпитер, който има значителен потенциал за бъдещи изследвания и използване на ресурси.

<<<<<<< HEAD
Симулацията започва с свободна камера, която позволява движение и въртене в 3D пространство с помощта на мишката и клавиатурата. Чрез натискане на цифровите клавиши 1-9 потребителите могат да превБутонват към стационарни орбитални камери, разположени на фиксирани места спрямо деветте планети. Освен това има и още шест стационарни камери, посветени на конкретни луни и Астероидния Пояс.
=======
Симулацията започва със свободна камера, която позволява движение и въртене в 3D пространство с помощта на мишка и клавиатура. Чрез натискане на числата от 1 до 9, потребителите могат да превключват на орбитални камери, разположени на фиксирани места спрямо деветте планети. Освен това има шест стационарни камери, посветени на конкретни луни и астероидния пояс.
>>>>>>> 41205a069236c262808840261ba591ee1ec0ab7a

Приложението ви позволява да регулирате скоростта на симулацията или да я паузирате по всяко време, което позволява подробно изучаване на движенията на небесните тела. То също така предоставя възможност за визуализация на орбитите на планетите и техните луни.

Докато много хора мечтаят да пътуват в космоса и се надявам това да стане реалност в близко бъдеще, 3D симулацията на Слънчевата система предлага възможността да управлявате виртуален космически кораб, изследвайки дестинации от Слънцето до Плутон.

<<<<<<< HEAD
<div align="center">
<video src="https://github.com/user-attachments/assets/5621b124-eda8-4a60-a70e-8077b35e10fe" />
</div>

=======
<p align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/start.jpg" width="854px"/>
</p>
>>>>>>> 41205a069236c262808840261ba591ee1ec0ab7a

# Основни етапи при реализирането на проекта

<<<<<<< HEAD
## Използвани технологии

- C++ -- Език за програмиране
- Microsoft Visual Studio - Среда за програмиране
- Assimp - assimp е библиотека, която зарежда различни 3D файлови формати.
- OpenGL - OpenGL е междуезичен, междуплатформен интерфейс за програмиране на приложения за изобразяване на 2D и 3D векторни графики.
- GLFW - Предоставя прост API за създаване на прозорци, контексти и повърхности, получаване на входни данни и събития.
- Github - GitHub е базирана на облак платформа, където можете да съхранявате, споделяте и да си сътрудничите с други, за да пишете код.
- Glm - C++ математически библиотеки за OpenGL
- GLSL - е език за засенчване на високо ниво, предназначен за писане на шейдъри
- FreeType2 - софтуерна библиотека с отворен код, предназначена за изобразяване на шрифтове
- SketchUp - популярен софтуер за 3D моделиране, използван за създаване, редактиране и споделяне на 3D дизайн
=======
- Дефиниране на идея
- Представяне на мениджър
- Определяне на техническите средства за разработка
- Планиране и формулиране на проекта
- Разработка на функционалност
- Тестване и корекция
- Публикуване и споделяне

# Използвани технологии

- C++ -- Програмен език
- Microsoft Visual Studio - Програмираща среда
- Assimp - библиотека за зареждане на различни 3D файлови формати
- OpenGL - платформа за рендиране на 2D и 3D векторна графика
- GLFW - предоставя API за създаване на прозорци, контексти и повърхности, получаване на вход и събития
- Github - платформа за съхранение и споделяне на код
- Glm - C++ математически библиотеки за OpenGL
- GLSL - висококачествен език за писане на шейдъри
- FreeType2 - библиотека за рендиране на шрифтове
- SketchUp - софтуер за 3D моделиране

## Използвани напреднали графични технологии

- <a href="https://learnopengl.com/Advanced-OpenGL/Cubemaps">CubeMap текстуриране </a>
- <a href="https://learnopengl.com/Getting-started/Textures">Мултитекстуриране </a>
- <a href="https://learnopengl.com/Advanced-OpenGL/Instancing">Инстанциране </a>
>>>>>>> 41205a069236c262808840261ba591ee1ec0ab7a

## Напреднали графични технологии
- <a href="https://learnopengl.com/Advanced-OpenGL/Cubemaps">CubeMap текстуриране </a>
- <a href="https://learnopengl.com/Getting-started/Textures">Мултитекстуриране </a>
- <a href="https://learnopengl.com/Advanced-OpenGL/Instancing">Инстансинг </a>

<<<<<<< HEAD
## Логическо и функционално описание на приложението

Програмата ви позволява да разглеждате различни гледни точки и луни, да сменяте камери и различни други промени с тези бутони, можете да премахвате или добавяте орбити, да стартирате специален режим за допълнителна информация и т.н.

### Клавиатура

- WASDQE – движение на камерата
- Стрелки, точка и пръскане – завъртане на изгледа
- 1 – 0 на клавиатурата – промяна на камерата към изглед на планети
- 1 – 6 на клавиатурата - промяна на камерата към изглед на луни
- R – промяна на фона
- Аз – влизам и излизам от космически кораб
- O – показване и скриване на орбити
- P – време на замразяване
- J – промяна на камерата към страничен изглед (в изглед на планета)
- K – покажи космически кораб
- L – промяна на езика
- Клавиатура (+, -) – промяна на скоростта на симулация
- Интервал – връщане към POV по подразбиране
- F1 – промяна на POV на freecam
- X - показва допълнителна информация (в изглед на планета)
- F - ПревБутонване на цял екран
- F7 - начало на пътуването

### Мишка

- ляв бутон - завъртане на изгледа
- бутон за превъртане - увеличаване/намаляване
- десен бутон - преместване на изглед

## Астероиден пояс
Изгледът на астероидния пояс се активира чрез натискане на клавиша 0:

<div align="center">
<video src="https://github.com/user-attachments/assets/d76c2d16-f179-4b75-b5a2-820e72480653" />
=======
Програмата позволява разглеждане на различни перспективи и луни, смяна на камери и множество други настройки чрез следните бутони. Можете да добавяте или премахвате орбити, да стартирате специален режим за допълнителна информация и др.

### Клавиатура
- WASD и стрелките – движение на камерата
- 1 – 0 на клавиатурата – смяна на камерата към изглед на планетите
- 1 – 6 на цифровата клавиатура – смяна на камерата към изглед на луните
- E – смяна на фона
- I – влизане и излизане от космически кораб
- O – показване на орбитите
- P – замразяване на времето
- J – смяна на камерата към страничен изглед (в изглед на планети)
- K – показване на космическия кораб
- L – смяна на езика
- (+, -) на цифровата клавиатура – смяна на скоростта на симулацията
- Space – връщане към стандартна перспектива
- F1 – промяна към свободна камера
- X – показване на допълнителна информация (в изглед на планети)
- F – превключване на цял екран

### Мишка
- Ляв бутон - движение по осите X и Z
- Скрол бутон - увеличение/намаление
- Десен бутон - завъртане
Камерата може да се движи с WASD (по осите X и Z) и стрелките за нагоре и надолу (по ос Y).

Изгледът на астероидния пояс се активира с натискане на клавиша 0:

<div align="center">
<video src="https://github.com/user-attachments/assets/be5c9336-0e81-4073-85fe-4ea2194f53cf" />
</div>

Подробна информация за астероидите може да се активира с клавиша X:

<div align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/AsteroidsInfo.jpg" width="854px"/>
>>>>>>> 41205a069236c262808840261ba591ee1ec0ab7a
</div>

## Астероиди от пояса на Кайпер

Изгледът на пояса на Кайпер се активира с клавиша 0 на цифровата клавиатура:

<div align="center">
<<<<<<< HEAD
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/AsteroidsInfo.jpg" width="854px"/>
</div>

## Астероиди на Кайпер

Има изглед на пояса на Кайпер с клавиша 0 на цифровата клавиатура:

<div align="center">
<video src="https://github.com/user-attachments/assets/b8023968-3bef-43a4-86d8-d0b5d058b8c4" />
</div>

Допълнителната информация за астероидния пояс на Кайпер се показва чрез натискане на бутона X
=======
<video src="https://github.com/user-attachments/assets/0b6606e0-db7d-4f38-b7c7-8b735ed6d391" />
</div>

<div align="center">
<video src="https://github.com/user-attachments/assets/cd090cc6-e5bf-4439-bfb7-1047c35fffd6" />
</div>

Допълнителната информация за пояса на Кайпер се показва с натискане на клавиша X
>>>>>>> 41205a069236c262808840261ba591ee1ec0ab7a

<div align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/AsteroidsKuiperInfo.jpg" width="854px"/>
</div>

<<<<<<< HEAD
## Пътуване

Можете да започнете пътуване, като натиснете бутона F7.

<div align="center">
<video src="https://github.com/user-attachments/assets/2155c13e-c825-4a8c-8121-8c39edd8124c" />
</div>
 
Показването на орбитите на планетите може да се вБутонва и изБутонва с помощта на клавиша "O" и тази функция работи както в нормален изглед, така и в изглед на планета.
=======
Показването на орбитите на планетите може да се включва и изключва с клавиша "O", като тази функция работи както в нормален, така и в изглед на планети.
>>>>>>> 41205a069236c262808840261ba591ee1ec0ab7a

<p align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Orbits.jpg" width="854px"/>
</p>

<<<<<<< HEAD
Можете да превключвате между следните изгледи на планетарни камери, като използвате клавишите 1-9 на клавиатурата:

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mercury.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Venus.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Earth.jpg" width="300px"/>
|:---:|:---:|:---:|
| *<b>Меркурий - Бутон:1 </b>* | *<b>Венера - Бутон: 2</b>* | *<b>Земя - Бутон:3</b>* |

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mars.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Jupiter.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Saturn.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Марс - Бутон: 4 </b>* | *<b>Юпитер - Бутон:5 </b>* | *<b>Сатурн - Бутон:6 </b>* |

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Neptune.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Uranus.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Pluto.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Нептун - Бутон:7 </b>* | *<b>Уран - Бутон:8 </b>* | *<b>Плутон - Бутон:9 </b>* |

Изгледът на планети и луни може да се превБутони към страничен орбитален изглед с клавиш J:

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mercury2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Venus2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Earth2.jpg" width="300px"/>
|:---:|:---:|:---:|
| *<b>Изглед отстрани на Меркурий - Бутон:1+J </b>* | *<b>Изглед отстрани на Венера - Бутон:2+J</b>* | *<b>Изглед от страната на Земята - Бутон:3+J</b>* |

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mars2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Jupiter2.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Saturn2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Изглед отстрани на Марс - Бутон:4+J </b>* | *<b>Изглед отстрани на Юпитер - Бутон:5+J </b>* | *<b>Страничен изглед на Сатурн - Бутон:6+J </b>* |

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Neptune2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Uranus2.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Pluto2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Изглед отстрани на Нептун - Бутон:7+J </b>* | *<b>Изглед отстрани на Уран - Бутон:8+J </b>* | *<b>Изглед отстрани на Плутон - Бутон:9 +J</b>* |
=======
Можете да превключвате между следните изгледи на планетарни камери, използвайки клавишите от 1 до 9 на клавиатурата:

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mercury.jpg" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Venus.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Earth.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Меркурий - Клавиш:1 </b>* | *<b>Венера  - Клавиш:2</b>* | *<b>Земя - Клавиш:3</b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mars.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Jupiter.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Saturn.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Марс - Клавиш:4 </b>* | *<b>Юпитер - Клавиш:5 </b>* | *<b>Сатурн - Клавиш:6 </b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Neptune.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Uranus.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Pluto.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Нептун - Клавиш:7 </b>* | *<b>Уран - Клавиш:8 </b>* | *<b>Плутон - Клавиш:9 </b>* | 

Изгледите на планети и луни могат да се превключват на страничен орбитален изглед с клавиша J:

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mercury2.jpg" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Venus2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Earth2.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Меркурий - Клавиш:1+J </b>* | *<b>Венера - Клавиш:2+J</b>* | *<b>Земя - Клавиш:3+J</b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mars2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Jupiter2.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Saturn2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Марс - Клавиш:4+J </b>* | *<b>Юпитер - Клавиш:5+J </b>* | *<b>Сатурн - Клавиш:6+J </b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Neptune2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Uranus2.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Pluto2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Нептун - Клавиш:7+J </b>* | *<b>Уран - Клавиш:8+J </b>* | *<b>Плутон - Клавиш:9 +J</b>* | 
>>>>>>> 41205a069236c262808840261ba591ee1ec0ab7a

Изгледи на луните (1–6 на цифровата клавиатура):

<<<<<<< HEAD
| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Moon2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Io2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Europa2.jpg" width="300px"/>
|:---:|:---:|:---:|
| *<b>Луна - Клавиатура:1</b>* | *<b>Io - клавиатура:2</b>* | *<b>Europa- KeyPad:3</b>* |

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Ganymede2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Callisto2.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Rhea2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Ганимед - клавиатура:4 </b>* | *<b>Callisto- KeyPad:5 </b>* | *<b>Rhea - Клавиатура:6 </b>* |

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Titan2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Oberon2.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Triton2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Titan - Клавиатура:7 </b>* | *<b>Oberon- KeyPad:8 </b>* | *<b>Triton - клавиатура:9 </b>* |

В изгледите на планети и луни има допълнителна информация за обектите, показани с клавиша X:

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/EarthInfo.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/MarsInfo.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/PlutoInfo.jpg" width="300px"/>
|:---:|:---:|:---:|
| *<b>Земя - Бутон:3+X</b>* | *<b>Марс - Бутон:4+X</b>* | *<b>Плутон- Бутон:9+X</b>* |

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/MoonInfo.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/CallistoInfo.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/TritonInfo.jpg" width="300px"/>
|:---:|:---:|:---:|
| *<b>Луна - Бутон:KP 1+X</b>* | *<b>Калисто - Бутон:KP 6+X</b>* | *<b>Тритон- Бутон:KP 9+X</b>* |
=======
| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Moon2.jpg" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Io2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Europa2.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Луна - Цифр. клавиатура:1</b>* | *<b>Ио - Цифр. клавиатура:2</b>* | *<b>Европа - Цифр. клавиатура:3</b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Ganymede2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Callisto2.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Rhea2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Ганимед - Цифр. клавиатура:4 </b>* | *<b>Калисто - Цифр. клавиатура:5 </b>* | *<b>Рея - Цифр. клавиатура:6 </b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Titan2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Oberon2.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Triton2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Титан - Цифр. клавиатура:7 </b>* | *<b>Оберон - Цифр. клавиатура:8 </b>* | *<b>Тритон - Цифр. клавиатура:9 </b>* | 

В изглед на планети и луни има допълнителна информация за обектите, която се показва с клавиша X:

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/EarthInfo.jpg" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/PlutoInfo.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/PlutoInfo.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Земя - Клавиш:3+X</b>* | *<b>Марс - Клавиш:4+X</b>* | *<b>Плутон - Клавиш:9+X</b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/MoonInfo.jpg" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/CallistoInfo.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/TritonInfo.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Луна - Клавиш:Цифр. клавиатура 1+X</b>* | *<b>Калисто - Клавиш:Цифр. клавиатура 6+X</b>* | *<b>Тритон - Клавиш:Цифр. клавиатура 9+X</b>* | 
>>>>>>> 41205a069236c262808840261ba591ee1ec0ab7a

Отново клавишите J и O могат да се използват за показване на орбитите на планетите:

<div align="center">
 <video src="https://github.com/user-attachments/assets/4a4b5588-219a-4aa4-bb61-bf4b96394c10" />
</div>

<div align="center">
 <video src="https://github.com/user-attachments/assets/44519ce4-bae0-4643-925b-45b4cee0c2d3" />
</div>

<div align="center">
<<<<<<< HEAD
 <video src="https://github.com/user-attachments/assets/d2270dc1-7ee5-40e9-98d3-667128fcc470"/>
</div>

## Предстоят още..

<ul>
 <li>Пътуване с космически кораб около слънчевата система </li>

 | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Spaceship1.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Spaceship2.jpg" width="300px"/> | <img src="pics/Spaceship3.jpg" width="300px"/>
 |:---:|:---:|:---:|
 <li>Избор на планети и взаимодействие </li>
 <li>Показване на вътрешната структура на планетите</li>
</ul>

## Почерпете вдъхновение от
* <a href="https://learnopengl.com">learnopengl</a> - обширен ресурс за обучение за изучаване на OpenGL
* <a href="https://www.solarsystemscope.com">solarsystemscope.com </a> - текстури на планетите в Слънчевата система
* <a href="https://sketchfab.com">sketchfab.com </a> - 3D модели на обекти
* <a href="https://github.com/1kar/OpenGL-SolarSystem">OpenGL-SolarSystem</a> - 3D C/C++/OpenGL/GLFW прост модел на слънчевата система

## Освобождаване
<b>SolarSystem 1.0 </b>можете да изтеглите от:
|Версия (<b>1.0</b>)| [SolarSystem.zip](https://github.com/danitmb/SolarSystem/raw/refs/heads/main/install/SolarSystem.zip)|
=======
 <video src="https://github.com/user-attachments/assets/2cb0302a-fcc6-4c19-9269-390e43d89f01" />
</div>

# Предстои още...
<ul>
  <li>Пътуване с космически кораб из Слънчевата система</li>
  
  | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Spaceship1.jpg" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Spaceship2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Spaceship3.jpg" width="300px"/> 
  |:---:|:---:|:---:|
  <li>Избор на планети и взаимодействие</li>
  <li>Показване на вътрешната структура на планетите</li>
</ul>

# Вдъхновение
* <a href="https://learnopengl.com">learnopengl

# Вдъхновен от
* <a href="https://learnopengl.com">learnopengl</a> - обширен учебен ресурс за изучаване на OpenGL
* <a href="https://www.solarsystemscope.com">solarsystemscope.com</a> - текстури на планетите в Слънчевата система
* <a href="https://sketchfab.com">sketchfab.com</a> - 3D модели на обекти
* <a href="https://github.com/1kar/OpenGL-SolarSystem">OpenGL-SolarSystem</a> - 3D модел на Слънчевата система на C/C++/OpenGL/GLFW

# Пускане
<b>Слънчева система 1.0</b> може да бъде изтеглена от:
|Версия (<b>1.0</b>)|  [SolarSystem.zip](https://github.com/danitmb/SolarSystem/raw/refs/heads/main/install/SolarSystem.zip)|
>>>>>>> 41205a069236c262808840261ba591ee1ec0ab7a
|---|---|
|Ръководство за потребителя| [SolarSystem.pdf](docs/SolarSystem.pdf)|

## Системни изисквания

Операционна система Windows 10/11
<br>
<<<<<<< HEAD
Видео карта, поддържаща OpenGL 4.x и 1GB памет
=======
Видео карта, която поддържа OpenGL 4.x и 1GB памет
>>>>>>> 41205a069236c262808840261ba591ee1ec0ab7a
