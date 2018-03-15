# Proyecto Carro Robot manejado por Emotiv Insight

Elaborado por el Laboratorio de Robotica en Internet de las Cosas - FISI - UNMSM con el objetivo de ser presentado en
el evento Arduino Day 2018 - Peru

## Resumen

Implementacion de una aplicacion de escritorio en C++ con el framework Qt, basada en el codigo de ejemplo compartido por
la empresa Emotiv en su repositorio de Github https://github.com/Emotiv/cortex-example/tree/master/cpp-qt.

La aplicacion permitira manejar la informacion del headset, obtenida del websocket de Emotiv, la cual sera almacenada en el servicio
de base de datos en tiempo real NoSQL Firebase.

Luego esta informacion sera consultada por un modulo esp8266 conectado a un carro robot basado en Arduino.
