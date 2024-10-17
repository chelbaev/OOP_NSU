установка googletest:

git clone https://github.com/google/googletest.git -b v1.15.2

cd googletest

mkdir build

cd build

cmake ..

для *nix систем:

make

sudo make install

запуск самого cmake:

cmake -S. -Bbuild  

cmake --build build

запуск main (не смотря на своё существование он крайне бесполезен):

./build/BA_main

запуск гугл тестов:

./build/tests/BA_test

папка lib - там лижит библиотека с классом BitArray

папка tests - там лежат тесты

main.cpp - само приложение

P.S. я хотел сделать документацию, но я не знаю как она делается, я обещаю вам её сделать как только вы мне скажите как это вообще делается
