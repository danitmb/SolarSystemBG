# 3D Слънчева Система

Автор: Даниел Милев <br>

<a href="https://github.com/danitmb/SolarSystem/raw/refs/heads/main/install/SolarSystem.zip">Свали</a>

# Въведение

Проектът има за цел да разработи 3D симулация на Слънчевата система с помощта на OpenGL и съвременни мултимедийни технологии. Тази симулация ще улесни изучаването на геометрията, позициите и орбиталните скорости на планетите и техните луни. Освен това има и изглед на Астероидния Пояс, разположен между Марс и Юпитер, който притежава значителен потенциал за бъдещо проучване и използването на ресурси.

Симулацията започва с свободна камера, която позволява движение и въртене в 3D пространство с помощта на мишката и клавиатурата. Чрез натискане на цифровите клавиши 1-9 потребителите могат да превБутонват към стационарни орбитални камери, разположени на фиксирани места спрямо деветте планети. Освен това има и още шест стационарни камери, посветени на конкретни луни и Астероидния Пояс.

Приложението ви позволява да регулирате скоростта на симулацията или да я поставите на пауза във всеки избран момент, което позволява подробно проучване на движенията на небесните тела. Също така има възможност за визуализиране на орбитите на планетите и техните луни.

Въпреки че мнозина мечтаят да пътуват до Космоса и се надявам това да стане реалност в близко бъдеще, 3D симулацията на Слънчевата Система предлага възможността да пилотирате виртуален космически кораб, изследвайки дестинации от Слънцето до Плутон.

<div align="center">
<video src="https://github.com/user-attachments/assets/5621b124-eda8-4a60-a70e-8077b35e10fe" />
</div>


# Основни етапи в реализирането на проекта

1. Определяне на идея
2. Представане на ръководителя
3. Определяне на технически средсва за разработване
4. Планиране и оформяне на проекта
5. Разработване на функционалност
6. Тестване и корекция
7. Публикуване и споделяне

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

## Напреднали графични технологии
- <a href="https://learnopengl.com/Advanced-OpenGL/Cubemaps">CubeMap текстуриране </a>
- <a href="https://learnopengl.com/Getting-started/Textures">Мултитекстуриране </a>
- <a href="https://learnopengl.com/Advanced-OpenGL/Instancing">Инстансинг </a>

## Логическо и функционално описание на приложението

Програмата ви позволява да разглеждате различни гледни точки и луни, да сменяте камери и различни други промени с тези бутони, можете да премахвате или добавяте орбити, да стартирате специален режим за допълнителна информация и т.н.

### Клавиатура

 - /(? - помощно меню
 - WASDQE – движение на камерата.
 - Стрелки – завъртане на изгледа спрямо осите X и Y.
 - < > – завъртане на изгледа спрямо оста Z.
 - 1 – 0 на клавиатурата – смяна на камерата към изглед на планетите
 - 1 – 6 на цифровия блок – смяна на камерата към изглед на луните
 - R – смяна на фона.
 - O – показване и скриване на орбитите
 - P – пауза
 - J – смяна на камерата към страничен изглед (в изглед на планета)
 - K – показване на космическия кораб
 - L – смяна на езика
 - (+, - – промяна на скоростта на симулацията
 - Space – връщане към стандартната гледна точка
 - F1 – превключване към свободна камера
 - X – показване на допълнителна информация (в изглед на планета)
 - F – превключване на цял екран
 - NM - смяна на броя на астероидите
 - HG - смяна на броя на астероидите на Кайпер
 - Z - показване на оси
 - B - показване на астероиден пояс
 - V - показване на пояса на Кайпер
### Мишка

- ляв бутон - завъртане на изгледа
- бутон за превъртане - увеличаване/намаляване
- десен бутон - преместване на изглед

## Астероиден пояс
Изгледът на астероидния пояс се активира чрез натискане на клавиша 0:

<div align="center">
<video src="https://github.com/user-attachments/assets/d76c2d16-f179-4b75-b5a2-820e72480653" />
</div>

Подробна информация за астероидите може да се активира с клавиш X:

<div align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/AsteroidsInfo.jpg" width="854px"/>
</div>

## Астероиди на Кайпер

Има изглед на пояса на Кайпер с клавиша 0 на цифровата клавиатура:

<div align="center">
<video src="https://github.com/user-attachments/assets/b8023968-3bef-43a4-86d8-d0b5d058b8c4" />
</div>

Допълнителната информация за астероидния пояс на Кайпер се показва чрез натискане на бутона X

<div align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/AsteroidsKuiperInfo.jpg" width="854px"/>
</div>

## Пръстени на Сатурн

Сатурновият пояс се състои от три подпоения, известни като A, B и C.
<div align="center">
 <video src="https://github.com/user-attachments/assets/5fe0d665-2acf-41b8-b2ae-a558ace83785"/>
</div>

Изглед на пътуване на камерата започва с натискането на клавиш F7.

<div align="center">
<video src="https://github.com/user-attachments/assets/2155c13e-c825-4a8c-8121-8c39edd8124c" />
</div>

Показването на орбитите на планетите може да се включва и изключва с клавиш "O", и тази функция работи както в нормален, така и в планетен изглед.

Можете да преминавате между следните изгледи на планетарните камери с помощта на клавишите 1-9 на клавиатурата:

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mercury.jpg" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Venus.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Earth.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Меркурий - Клавиш:1 </b>* | *<b>Венера  - Клавиш:2</b>* | *<b>Земя - Клавиш:3</b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mars.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Jupiter.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Saturn.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Марс - Клавиш:4 </b>* | *<b>Юпитер - Клавиш:5 </b>* | *<b>Сатурн - Клавиш:6 </b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Neptune.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Uranus.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Pluto.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Нептун - Клавиш:7 </b>* | *<b>Уран - Клавиш:8 </b>* | *<b>Плутон - Клавиш:9 </b>* | 

Изгледите на планетите и луните могат да бъдат превключени към страничен орбитален изглед с клавиш J:

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mercury2.jpg" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Venus2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Earth2.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Страничен изглед на Меркурий - Клавиш:1+J </b>* | *<b>Страничен изглед на Венера - Клавиш:2+J</b>* | *<b>Страничен изглед на Земя - Клавиш:3+J</b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mars2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Jupiter2.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Saturn2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Страничен изглед на Марс - Клавиш:4+J </b>* | *<b>Страничен изглед на Юпитер - Клавиш:5+J </b>* | *<b>Страничен изглед на Сатурн - Клавиш:6+J </b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Neptune2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Uranus2.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Pluto2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Страничен изглед на Нептун - Клавиш:7+J </b>* | *<b>Страничен изглед на Уран - Клавиш:8+J </b>* | *<b>Страничен изглед на Плутон - Клавиш:9 +J</b>* | 

Изгледи на камерата за някои от луните (1–6 на цифровата клавиатура):

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Moon2.jpg" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Io2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Europa2.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Луна - Клавиш:1</b>* | *<b>Ио - Клавиш:2</b>* | *<b>Европа- Клавиш:3</b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Ganymede2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Callisto2.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Rhea2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Ганимед - Клавиш:4 </b>* | *<b>Калипсо- Клавиш:5 </b>* | *<b>Рея - Клавиш:6 </b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Titan2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Oberon2.jpg" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Triton2.jpg" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Титан - Клавиш:7 </b>* | *<b>Оберон- Клавиш:8 </b>* | *<b>Тритон - Клавиш:9 </b>* | 

В изгледите на планетите и луните има допълнителна информация за показваните обекти с клавиш X:

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/EarthInfo.jpg" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/MarsInfo.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/PlutoInfo.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Земя - Клавиш:3+X</b>* | *<b>Марс - Клавиш:4+X</b>* | *<b>Плутон- Клавиш:9+X</b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/MoonInfo.jpg" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/CallistoInfo.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/TritonInfo.jpg" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Луна - Клавиш:KP 1+X</b>* | *<b>Калипсо - Клавиш:KP 6+X</b>* | *<b>Тритон- Клавиш:KP 9+X</b>* | 

Отново клавишите J и O могат да се използват за показване на орбитите на планетите:

<div align="center">
 <video src="https://github.com/user-attachments/assets/d5fa2e72-c69d-4172-8541-b1b3d5ab8889" />
</div>

<div align="center">
 <video src="https://github.com/user-attachments/assets/3f7a4180-77c4-4103-9bba-f2391ade11f0" />
</div>

## Предстоят още..

<ul>
 <li>Пътуване с космически кораб около слънчевата система </li>

 | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Spaceship1.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Spaceship2.jpg" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Spaceship3.jpg" width="300px"/>
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
|---|---|
|Ръководство за потребителя| [SolarSystem.pdf](docs/SolarSystem.pdf)|

## Системни изисквания

Windows OS 10/11
<br>
Видео карта, поддържаща OpenGL 4.x и 1GB памет