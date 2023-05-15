![MapOfComputerScience.jpg](MapOfComputerScience.jpg)

Привет! :smiley:  
Мой репозиторий посвящен программированию на всех уровнях абстракции. От создания низкоуровневой логики процессора, операционной системы и компилятора...  
...до высокоуровневых пользовательских приложений - баз данных, web, блокчейн, нейронных сетей и 3D-графики.

Такой широкий охват технологий выбран не случайно. Он опирается на инженерную теорию управления сложностью и системный подход в науке.  
:one:Первая утверждает, что любую сложную систему можно собрать из числа простых систем, каждая из которых состоит из числа еще более простых систем.  
:two:Второй - что изучая или проектируя новую систему не достаточно понять ее собственное устройство, но также необходимо изучить устройство той более крупной системы, частью которой она является.

:dart: Центральной точкой притяжения, объединяющей компьютерные технологии в единое целое, является операционная система. Процесс её создания включает проектирование микропроцессорной системы и описание структур и алгоритмов ядра операционной системы. Вместе они создают пространство для исполнения прикладных программ.

Каждая прикладная программа в такой системе видит свой плоский объем памяти, обладает квантом процессорного времени и для связи с внешними устройствами или другими программами использует вызовы ядра операционной системы. Внутри плоского объема памяти программа хранит свои структуры и алгоритмы. Если в прикладной программе разместить структуры и алгоритмы ядра операционной системы, то получим операционную систему внутри операционной системы.  
:exclamation: :sparkles: Если опуститься глубже и дополнительно разместить внутри прикладной программы структуры и алгоритмы, которые содержит микропроцессор, то мы получим компьютер внутри компьютера :sparkles: :exclamation:

Так есть возможность создавать неограниченное число компьютеров всех видов архитектур, как существующих, так и придумывать новые. Интересным выглядит тот методологический факт, что мы можем не только запустить машину Тьюринга на современном Core i7, но и запустить Core i7 на машине Тьюринга :wink:

Поэтому ведущим проектом репозитория, который объединяет вокруг себя остальные, выбрана собственная операционная система [OS Doors](https://github.com/GorComComputing/OS_Doors32).  
:bulb: Сейчас я разрабатываю 3-ю версию, исполняющуюся на процессорах IA-32, ARM32, MIPS32 и RISC-V.  
Операционная система POSIX-совместима, что позволяет создавать прикладные программы под Linux до того, как я завершу собственное ядро. Это означает, что программы для доступа к структурам и алгоритмам ядра используют общие для всех Unix-систем функции, а само ядро внутри может быть устроено на усмотрение программиста любым образом.
Такой подход позволяет мне гибко заниматься разработкой системы как сверху, так и снизу одновременно.

:checkered_flag: Я работаю над этим каждый день, и в результате прохождения всех уровней я получу собственный процессор со своим машинным кодом, собственный компилятор и язык программирования для него. На этом языке будет написана операционная система с графическим интерфейсом и поддержкой сетевых протоколов TCP/IP. А поверх операционной системы будут запускаться собственные web-серверы, браузеры, базы данных... виртуальные машины других компьютеров со своими системами... и другие пользовательские приложения.

Многое из этого я уже сделал. Многое предстоит. На вопрос: зачем мне это? - отвечу словами физика нобелевского лауреата:smiley::  
> *Что я не могу создать, я не понимаю (с) Ричард Фейнман*

<!--div id="header" align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNjgzYWFiMTY0ZTA2MzM0YzU3NGYwM2VhZjdlMzUwOTg5YWU1MTA3MCZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/SmaYvew52UlC9MmB6l/giphy.gif" width="200"/>
</div-->

<div id="header" align="center">
  <img src="https://media.giphy.com/media/3ohc157IyQlpWtqbug/giphy.gif" width="100"/>
</div>



<!--## Операционная система Doors
##### Ядро
* [Ядро Doors для i386]() (на C и Assembly i386)
* [Ядро Doors для ARM]() (на C и Assembly ARM)
##### Приложения
* [Командный интерпретатор Shell]() (на C)
* [Оконный графический интерфейс]() (на C)
* [Компилятор]() (на C)
* [Виртуальная машина]() (на C)
* [СУБД SQLite]() (на C)
* [Web Server]() (на C)
##### Библиотеки
* [Библиотека системных вызовов Doors для i386]() (на C и Assembly i386)
* [Библиотека системных вызовов Doors для ARM]() (на C и Assembly ARM)
* [Библиотека работы со строками]() (на C)
* [Математическая библиотека]() (на C)
* [Графическая библиотека]() (на C)
* [Библиотека абстрактных типов данных]() (на C)-->


<!--div id="header" align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2YzYmEwNjk5NGVlNjY4ZjRmNDQ4YmZkNTExMzE5ZjY5YzQ3YjM4NCZlcD12MV9pbnRlcm5hbF9naWZzX2dpZklkJmN0PWc/3oEjHGJE2H5KMDjyj6/giphy.gif" width="200"/>
</div-->


## Мои проекты
##### Операционные системы
* [Операционная система Doors 3](https://github.com/GorComComputing/OS_Doors3) (на C и Assembly i386, ARM32, MIPS32, RISC-V) - `в разработке` :clock10:
* [Операционная система Doors 2 (32-бит)](https://github.com/GorComComputing/OS_Doors32) (на C и Assembly i386)
* [Оконный графический интерфейс (для операционной системы Doors)](https://github.com/GorComComputing/GUI_Window) (на C)
##### Компиляторы и виртуальные машины
* [Компилятор и ассемблер для процессора 8-bit-AON](https://github.com/GorComComputing/C_Compiler) (в Delphi XE 10.3)
* [Виртуальный процессор 8-bit-AON](https://github.com/GorComComputing/8-bit-AON-Computer) (на JavaScript)
* [Компилятор языка Oberon для стековой виртуальной машины OVM](https://github.com/GorComComputing/Oberon_Compiler) (на Python)
##### Компьютерная графика
* [Графическая библиотека](https://github.com/GorComComputing/Graphics) (на C)
* [Игра (использование библиотеки PyGame)](https://github.com/GorComComputing/Game_PyGame) (на Python) 
##### Командные интерпретаторы
* [Shell для Linux](https://github.com/GorComComputing/Shell) (на C)
* [Basic 512 байт (в загрузочный сектор)](https://github.com/GorComComputing/Basic512) (на Assembly x86)
##### Базы данных
* [СУБД SQLite](https://github.com/GorComComputing/SQLite) (на C)
* [Библиотека абстрактных типов данных](https://github.com/GorComComputing/Algorithms) (на C++)
##### Embedded
* [Игра на микроконтроллере ATmega328](https://github.com/GorComComputing/Game_Arduino) (на C++ Arduino)
* [Basic на микроконтроллере ATmega328](https://github.com/GorComComputing/Basic_TCP_Arduino) (на C++ Arduino)
##### Web front-end
* [Framework.js](https://github.com/GorComComputing/Framework.js) (на JavaScript)
##### Web back-end
* [Web Server](https://github.com/GorComComputing/Web_Server) (на C)
* [Web Server (Сайт на Ассемблере)](https://github.com/GorComComputing/Site_on_Asm) (на Assembly i386)
* [Сайт по электронике]() (на Python Django) - `в разработке` :clock10:
##### Сети
* [Чат клиент-сервер (TCP)](https://github.com/GorComComputing/Chat_TCP) (на C)
* [Чат p2p (TCP)](https://github.com/GorComComputing/p2p_chat) (на Python)
##### Blockchain
* [Blockchain](https://github.com/GorComComputing/Blockchain) (на Python)
##### Автоматизированное тестирование
* [Бот для Tinder](https://github.com/GorComComputing/AutoTinder) (на Python)
##### Программная инжинирия
* [Git](https://github.com/GorComComputing/Git) (на Python) - `в разработке` :clock10:
##### Виртуализация
* [Docker](https://github.com/GorComComputing/Docker) (на C) - `в разработке` :clock10:
##### 1С:Предприятие
* [1С:Дневник](https://github.com/GorComComputing/1C_Diary) (в 1С:Предприятие 8.3)
##### Мобильные приложения
* [Мобильная игра Driver](https://github.com/GorComComputing/Driver_J2ME) (на Java ME) - `написана в 2007 году` :calendar:



## Технологии, используемые в проектах:

<div id="header" align="center">
<img src="https://github.com/devicons/devicon/blob/master/icons/c/c-line.svg" title="C" alt="C" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/cplusplus/cplusplus-line.svg" title="C++" alt="C++" width="20" height="20"/>&nbsp;
<!--img src="https://github.com/devicons/devicon/blob/master/icons/cmake/cmake-original-wordmark.svg" title="cmake" alt="cmake" width="20" height="20"/>&nbsp;-->
<img src="https://github.com/devicons/devicon/blob/master/icons/arduino/arduino-original-wordmark.svg" title="Arduino" alt="Arduino" width="20" height="20"/>&nbsp;
<!--img src="https://github.com/devicons/devicon/blob/master/icons/bash/bash-original.svg" title="Bash" alt="Bash" width="20" height="20"/>&nbsp;-->
<img src="https://github.com/devicons/devicon/blob/master/icons/qt/qt-original.svg" title="qt" alt="qt" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/linux/linux-original.svg" title="linux" alt="linux" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/sdl/sdl-original.svg" title="sdl" alt="sdl" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/opengl/opengl-original.svg" title="opengl" alt="opengl" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original-wordmark.svg" title="python" alt="python" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/django/django-plain-wordmark.svg" title="django" alt="django" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/flask/flask-original-wordmark.svg" title="flask" alt="flask" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/selenium/selenium-original.svg" title="selenium" alt="selenium" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/html5/html5-original-wordmark.svg" title="html5" alt="html5" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/css3/css3-original-wordmark.svg" title="css3" alt="css3" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/bootstrap/bootstrap-original-wordmark.svg" title="bootstrap" alt="bootstrap" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-original.svg" title="javascript" alt="javascript" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/jquery/jquery-original-wordmark.svg" title="jquery" alt="jquery" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/typescript/typescript-original.svg" title="typescript" alt="typescript" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original-wordmark.svg" title="react" alt="react" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/vuejs/vuejs-original-wordmark.svg" title="vuejs" alt="vuejs" width="20" height="20"/>&nbsp;
<!--img src="https://github.com/devicons/devicon/blob/master/icons/embeddedc/embeddedc-original-wordmark.svg" title="embeddedc" alt="embeddedc" width="20" height="20"/>&nbsp;-->
<!--img src="https://github.com/devicons/devicon/blob/master/icons/gcc/gcc-original.svg" title="gcc" alt="gcc" width="20" height="20"/>&nbsp;-->
<img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="git" alt="git" width="20" height="20"/>&nbsp;
<!--img src="https://github.com/devicons/devicon/blob/master/icons/github/github-original-wordmark.svg" title="github" alt="github" width="20" height="20"/>&nbsp;-->
<img src="https://github.com/devicons/devicon/blob/master/icons/java/java-original-wordmark.svg" title="java" alt="java" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/tomcat/tomcat-original-wordmark.svg" title="tomcat" alt="tomcat" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/spring/spring-original-wordmark.svg" title="spring" alt="spring" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/php/php-original.svg" title="php" alt="php" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/laravel/laravel-plain-wordmark.svg" title="laravel" alt="laravel" width="20" height="20"/>&nbsp;
<!--img src="https://github.com/devicons/devicon/blob/master/icons/markdown/markdown-original.svg" title="markdown" alt="markdown" width="20" height="20"/>&nbsp;-->
<img src="https://github.com/devicons/devicon/blob/master/icons/yii/yii-original-wordmark.svg" title="yii" alt="yii" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/modx/modx-original-wordmark.svg" title="modx" alt="modx" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original-wordmark.svg" title="postgresql" alt="postgresql" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/mysql/mysql-original-wordmark.svg" title="mysql" alt="mysql" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/sqlite/sqlite-original-wordmark.svg" title="sqlite" alt="sqlite" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/mongodb/mongodb-original-wordmark.svg" title="mongodb" alt="mongodb" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/redis/redis-original-wordmark.svg" title="redis" alt="redis" width="20" height="20"/>&nbsp;
<!--img src="https://github.com/devicons/devicon/blob/master/icons/nginx/nginx-original.svg" title="nginx" alt="nginx" width="30" height="20"/>&nbsp;-->
<!--img src="https://github.com/devicons/devicon/blob/master/icons/nodejs/nodejs-original-wordmark.svg" title="nodejs" alt="nodejs" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original-wordmark.svg" title="numpy" alt="numpy" width="20" height="20"/>&nbsp;-->
<!--img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original-wordmark.svg" title="pandas" alt="pandas" width="20" height="20"/>&nbsp;-->
<!--img src="https://github.com/devicons/devicon/blob/master/icons/putty/putty-original.svg" title="putty" alt="putty" width="20" height="20"/>&nbsp;-->
<img src="https://github.com/devicons/devicon/blob/master/icons/ruby/ruby-original-wordmark.svg" title="ruby" alt="ruby" width="20" height="20"/>&nbsp;
<img src="https://github.com/devicons/devicon/blob/master/icons/rails/rails-original-wordmark.svg" title="rails" alt="rails" width="20" height="20"/>&nbsp;
<!--img src="https://github.com/devicons/devicon/blob/master/icons/raspberrypi/raspberrypi-line-wordmark.svg" title="raspberrypi" alt="raspberrypi" width="20" height="20"/>&nbsp; -->
<!--img src="https://github.com/devicons/devicon/blob/master/icons/rspec/rspec-original-wordmark.svg" title="rspec" alt="rspec" width="20" height="20"/>&nbsp;-->
<!--img src="https://github.com/devicons/devicon/blob/master/icons/tensorflow/tensorflow-line-wordmark.svg" title="tensorflow" alt="tensorflow" width="20" height="20"/>&nbsp;-->
<img src="https://github.com/devicons/devicon/blob/master/icons/terraform/terraform-original-wordmark.svg" title="terraform" alt="terraform" width="20" height="20"/>&nbsp;

</div>

##### Микропроцессорные системы<!--Embedded-->:
- **Assembly**: x86-64, ARM, MIPS, RISC-V, AVR, Xtensa, MCS-51   
- **C**: Linux Kernel, FreeRTOS
- **C++**: Arduino<!--[ATmega328](https://github.com/stars/GorComComputing/lists/embedded), ESP32/8266, STM32 --> 

##### Приложения под <!--Desktop (-->Linux, Windows<!--, FreeBSD --><!--)-->:
- **C**: POSIX, WinAPI, OpenGL, GTK
- **C++**: <!--STL,--> SFML, SDL, Qt, wxWidgets, FLTK, Tcl/Tk, C++ Builder  
- **Python**: Qt, GTK, wxPython, pyFLTK, TkInter, NumPy, Pandas, Matplotlib, PyGame(SDL)  
- **Delphi**
- **Java**

##### Web back-end:
- **Java**: Spring, Hibernate, JDBC, Tomcat, JSP, JSTL <!--, gRPC , Lombok-->  
- **Python**: Django, Flask  
- **PHP**: Laravel, Yii, Modx, 1C:Bitrix
<!-- - **Ruby**: Ruby on Rails-->
<!-- - **Node.js**: Express.js -->

##### Web front-end:
- **JavaScript**: React, Angular, JQuery <!-- Vue.js --> <!-- - **TypeScript** -->
- **C++**: WebAssembly
- **HTML** & **CSS**: Bootstrap

##### Базы данных:
- **SQL**: MySQL, PostgreSQL, SQLite
- **NoSQL**: MongoDB, Redis 

<!-- ##### Системы сборки:
- **C**/**C++**: Make, CMake
- **Java**: Maven --> <!-- , Ant+Ivy, Gradle, Jenkins -->

##### Автоматизированное тестирование:
- **Java**: JUnit  
- **Python**: Selenium 
- **Ruby**: RSpec

<!-- ##### Программный инжиниринг: -->
<!-- - **ОС**: Windows, Linux, FreeBSD --> <!--, Unix -->
<!-- - **CLI**: Bash, Cmd, PowerShell
- **Контроль версий**: [Git](https://github.com/GorComComputing/Git) и GitHub --> <!-- , SVN -->
<!-- - **Архитектура**: UML, BPMN, Archimate -->
 <!-- - **Управление проектами**: RUP, PMI, SCRUM, Kanban --> 

<!-- ##### Облачные архитектуры:
- **Yandex.Cloud**: Terraform, Ansible --> <!-- - **Hypervisor**: ESXi, mRemoteNG -->
<!-- - **Контейнеры**: Docker, Kubernetes -->









---

### :fire: My Stats :
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=GorComComputing&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)

### Мои контакты
Евгений Горячев  
[![](https://img.shields.io/badge/Telegram-@extendedsuperbass-informational?style=flat&logo=telegram&logoColor=white&color=31a2db)](https://t.me/extendedsuperbass)<br/>
<a href="mailto:gorcom2012@gmail.com">![](https://img.shields.io/badge/Gmail-GorCom2012@gmail.com-informational?style=flat&logo=gmail&logoColor=white&color=e04a3e)</a>

