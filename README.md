# 3D Слънчева Система
Delevoper: Daniel Milev <br>

<a href="https://github.com/danitmb/SolarSystem/raw/refs/heads/main/install/SolarSystem.zip">Download</a>

# Въведение

Проектът има за цел да разработи 3D симулация на Слънчевата система с помощта на OpenGL и съвременни мултимедийни технологии. Тази симулация ще улесни изучаването на геометрията, позициите и орбиталните скорости на планетите и техните луни. Освен това има и изглед на Астероидния Пояс, разположен между Марс и Юпитер, който притежава значителен потенциал за бъдещо проучване и използването на ресурси.

Симулацията започва с свободна камера, която позволява движение и въртене в 3D пространство с помощта на мишката и клавиатурата. Чрез натискане на цифровите клавиши 1-9 потребителите могат да превключват към стационарни орбитални камери, разположени на фиксирани места спрямо деветте планети. Освен това има и още шест стационарни камери, посветени на конкретни луни и Астероидния Пояс.

Приложението ви позволява да регулирате скоростта на симулацията или да я поставите на пауза във всеки избран момент, което позволява подробно проучване на движенията на небесните тела. Също така има възможност за визуализиране на орбитите на планетите и техните луни.

Въпреки че мнозина мечтаят да пътуват до Космоса и се надявам това да стане реалност в близко бъдеще, 3D симулацията на Слънчевата Система предлага възможността да пилотирате виртуален космически кораб, изследвайки дестинации от Слънцето до Плутон.

<p align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/start.jpg?raw=true" width="854px"/>
</p>

# Основни етапи в реализирането на проекта

1. Определяне на идея
2. Представане на ръководителя
3. Определяне на технически средсва за разработване
4. Планиране и оформяне на проекта
5. Разработване на функционалност
6. Тестване и корекция
7. Публикуване и споделяне


# Използвани технологии

- C++ - език за програмиране
- Microsoft Visual Studio - среда за програмиране
- Assimp - библиотека, която зарежда различни 3D файлови формати
- FreeType2 - софтуерна библиотека с отворен код, предназначена за изобразяване на шрифтове
- OpenGL - междуезичен, междуплатформен интерфейс за програмиране на приложения за изобразяване на 2D и 3D векторни графики
- Glm - C++ математическа библиотека за OpenGL
- GLFW - Предоставя прост API за създаване на прозорци, контексти и повърхности, получаване на входни данни и събития
- GLSL - език за засенчване на високо ниво, предназначен за писане на шейдъри
- SketchUp - популярен софтуер за 3D моделиране, използван за създаване, редактиране и споделяне на 3D дизайн
- Github - GitHub е базирана на облак платформа, където можете да съхранявате, споделяте и да си сътрудничите с други, за да пишете код

# Логическо и функционално описание на приложението

Програмата предоставя възможност за изследване на всяка отделна планета от различни перспективи. Тя позволява на потребителите да се озоват в Астероидния пояс и да получат задълбочена информация за планетите.

### Клавиатура

- WASD и стрелки – движение на изглед;
- 1 – 0 на клавиатурата – промяна на изглед към изглед на планети;
- 1 – 6 на клавиатурата - промяна на изглед към изглед на луни;
- E – промяна на фона;
- I – влизане и излизане от космически кораб;
- O – показва орбити;
- P – пауза;
- J – промяна към страничен изглед (в изглед на планета);
- K – покажи космически кораб;
- L – промяна на езика;
- Клавиатура (+, -) – промяна на скоростта на симулация;
- Интервал – връщане към изгледа по подразбиране;
- F1 – промяна на изгледа на freecam;
- X - показва допълнителна информация (в изглед на планета);
- F – превключване между цял екран и прозорец;





### Mouse
- left button - panning in X and Z axis
- scroll button - zoom in/out
- right button - rotate

Camera view can be moved with WASD (in X and Z axis) and Arrows for up and down (in Y axis).

<div align="center">
<video src="https://github.com/user-attachments/assets/93e99bb8-7f29-4a39-b89f-99a0e82a597e" />
</div>

Asteroid belt view is activated by pressing the 0 key:

<div align="center">
<video src="https://github.com/user-attachments/assets/b8a709a6-67bc-4fda-bf5d-5f1afc7a1ef3" />
</div>

Detailed info of asteroids can be activated with X key:

<div align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/AsteroidsInfo.jpg?raw=true" width="854px"/>
</div>

The display of planet orbits can be toggled on and off using the "O" key, and this feature works in both normal and planet views.

<p align="center">
<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Orbits.jpg?raw=true" width="854px"/>
</p>



You can switch between the following planetary camera views using the 1-9 keys on the keyboard:

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mercury.jpg?raw=true" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Venus.jpg?raw=true" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Earth.jpg?raw=true" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Mercury - Key:1 </b>* | *<b>Venus  - Key:2</b>* | *<b>Earth - Key:3</b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mars.jpg?raw=true" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Jupiter.jpg?raw=true" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Saturn.jpg?raw=true" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Mars - Key:4 </b>* | *<b>Jupiter - Key:5 </b>* | *<b>Saturn - Key:6 </b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Neptune.jpg?raw=true" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Uranus.jpg?raw=true" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Pluto.jpg?raw=true" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Neptune - Key:7 </b>* | *<b>Uranus - Key:8 </b>* | *<b>Pluto - Key:9 </b>* | 

Planets and moons view can be switched to side orbital view with J key:

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mercury2.jpg?raw=true" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Venus2.jpg?raw=true" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Earth2.jpg?raw=true" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Mercury Side View - Key:1+J </b>* | *<b>Venus Side View - Key:2+J</b>* | *<b>Earth  Side View- Key:3+J</b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Mars2.jpg?raw=true" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Jupiter2.jpg?raw=true" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Saturn2.jpg?raw=true" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Mars Side View - Key:4+J </b>* | *<b>Jupiter Side View- Key:5+J </b>* | *<b>Saturn Side View - Key:6+J </b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Neptune2.jpg?raw=true" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Uranus2.jpg?raw=true" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Pluto2.jpg?raw=true" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Neptune Side View - Key:7+J </b>* | *<b>Uranus Side View - Key:8+J </b>* | *<b>Pluto Side View - Key:9 +J</b>* | 

Camera views for several of the moons (1–6 on the keypad):

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Moon2.jpg?raw=true" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Io2.jpg?raw=true" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Europa2.jpg?raw=true" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Moon - KeyPad:1</b>* | *<b>Io - KeyPad:2</b>* | *<b>Europa- KeyPad:3</b>* | 

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Ganymede2.jpg?raw=true" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Callisto2.jpg?raw=true" width="300px"/>|<img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Triton.jpg?raw=true" width="300px"/>|
|:---:|:---:|:---:|
| *<b>Ganymede - KeyPad:4 </b>* | *<b>Callisto- KeyPad:5 </b>* | *<b>Triton - KeyPad:6 </b>* | 

In planet views there is additional information about the planets displayed with X key:

| <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/EarthInfo.jpg?raw=true" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/MarsInfo.jpg?raw=true" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/PlutoInfo.jpg?raw=true" width="300px"/> 
|:---:|:---:|:---:|
| *<b>Earth - Key:3+X</b>* | *<b>Mars - Key:4+X</b>* | *<b>Pluto- Key:9+X</b>* | 

Again J and O keys can be used to display planet orbits:

<div align="center">
 <video src="https://github.com/user-attachments/assets/4a4b5588-219a-4aa4-bb61-bf4b96394c10" />
</div>

<div align="center">
 <video src="https://github.com/user-attachments/assets/44519ce4-bae0-4643-925b-45b4cee0c2d3" />
</div>

# More to come..
<ul>
  <li>Spacehip travel around the solar system </li>
  
  | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Spaceship1.jpg?raw=true" width="300px"/> |  <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Spaceship2.jpg?raw=true" width="300px"/> | <img src="https://github.com/danitmb/SolarSystem/blob/main/pics/Spaceship3.jpg?raw=true" width="300px"/> 
  |:---:|:---:|:---:|
  <li>Selection of planets and interaction </li>
  <li>Showing planets internal structure</li>
</ul> 

# Drew inspiration from
* <a href="https://learnopengl.com">learnopengl</a> - extensive tutorial resource for learning OpenGL
* <a href="https://www.solarsystemscope.com">solarsystemscope.com </a> - textures of the planets in the Solar system
* <a href="https://sketchfab.com">sketchfab.com </a> - 3D object models
* <a href="https://github.com/1kar/OpenGL-SolarSystem">OpenGL-SolarSystem</a> - 3D C/C++/OpenGL/GLFW Simple Solar System model

# Release
<b>SolarSystem 1.0 </b>can be downloaded from: 
|Version (<b>1.0</b>)|  [SolarSystem.zip](https://github.com/danitmb/SolarSystem/raw/refs/heads/main/install/SolarSystem.zip)|
|---|---|
|User Manual| [SolarSystem.pdf](docs/SolarSystem.pdf)|

## System Requirments

Windows OS 10/11
<br>
Video card supporting OpenGL 4.x and 1GB memory