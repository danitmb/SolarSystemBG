# 3D Слънчева система
Разработчик: Даниел Милев <br>

<a href="https://github.com/danitmb/SolarSystem/raw/refs/heads/main/install/SolarSystem.zip">Свали</a>

# Въведение

Проектът има за цел да разработи 3D симулация на Слънчевата система, използвайки OpenGL и съвременни мултимедийни технологии. Тази симулация ще улесни изучаването на геометрията, позициите и орбиталните скорости на планетите и техните луни. Освен това, тя предлага общ преглед на астероидния пояс, разположен между Марс и Юпитер, който има значителен потенциал за бъдещи изследвания и използване на ресурси.

Симулацията започва със свободна камера, която позволява движение и въртене в 3D пространство с помощта на мишка и клавиатура. Чрез натискане на числата от 1 до 9, потребителите могат да превключват на орбитални камери, разположени на фиксирани места спрямо деветте планети. Освен това има шест стационарни камери, посветени на конкретни луни и астероидния пояс.

Приложението ви позволява да регулирате скоростта на симулацията или да я паузирате по всяко време, което позволява подробно изучаване на движенията на небесните тела. То също така предоставя възможност за визуализация на орбитите на планетите и техните луни.

Докато много хора мечтаят да пътуват в космоса и се надявам това да стане реалност в близко бъдеще, 3D симулацията на Слънчевата система предлага възможността да управлявате виртуален космически кораб, изследвайки дестинации от Слънцето до Плутон.

<p align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/start.jpg" width="854px"/>
</p>

# Основни етапи при реализирането на проекта

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

# Логическо и функционално описание на приложението

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
<video src="https://github.com/user-attachments/assets/d2a3ac43-2120-4f64-963b-7fc302c3c72d" />
</div>

Подробна информация за астероидите може да се активира с клавиша X:

<div align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/AsteroidsInfo.jpg" width="854px"/>
</div>

## Астероиди от пояса на Кайпер

Изгледът на пояса на Кайпер се активира с клавиша 0 на цифровата клавиатура:

<div align="center">
<video src="https://github.com/user-attachments/assets/b7320a26-fe4c-4018-aace-eb966d712971" />
</div>

<div align="center">
<video src="https://github.com/user-attachments/assets/cd410638-9a8c-4ca7-805a-06d684e070ba" />
</div>

Допълнителната информация за пояса на Кайпер се показва с натискане на клавиша X

<div align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/AsteroidsKuiperInfo.jpg" width="854px"/>
</div>

Показването на орбитите на планетите може да се включва и изключва с клавиша "O", като тази функция работи както в нормален, така и в изглед на планети.

<p align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Orbits.jpg" width="854px"/>
</p>

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

Изгледи на луните (1–6 на цифровата клавиатура):

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

Отново клавишите J и O могат да се използват за показване на орбитите на планетите:

<div align="center">
 <video src="https://github.com/user-attachments/assets/4a4b5588-219a-4aa4-bb61-bf4b96394c10" />
</div>

<div align="center">
 <video src="https://github.com/user-attachments/assets/44519ce4-bae0-4643-925b-45b4cee0c2d3" />
</div>

<div align="center">
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
|---|---|
|Ръководство за потребителя| [SolarSystem.pdf](docs/SolarSystem.pdf)|

## Системни изисквания

Операционна система Windows 10/11
<br>
Видео карта, която поддържа OpenGL 4.x и 1GB памет
