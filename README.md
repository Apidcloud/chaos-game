# Chaos Game

![with-coffee](https://img.shields.io/badge/made%20with-%E2%98%95%EF%B8%8F%20coffee-yellow.svg)
![with-water](https://img.shields.io/badge/made%20with-%F0%9F%92%A7%20water-blue.svg)
![with-love](https://img.shields.io/badge/made%20with-%F0%9F%92%8C-red.svg)

This project generates different fractals with the Chaos Game, through the use of Plotly. For instance, Sierpinski triangle, can be generated by starting with 3 vertices (V1, V2, V3), and a (pseudo-)random starting point within the boundaries of the triangle made with said vertices. In each iteration, a vertex is chosen (pseudo-)randomly. A new point (n) is then created and directed to the chosen vertex and placed at half the distance between the chosen vertex and the last added point (n-1). After a few hundred iterations, the silhouette of the Sierpinsky triangle starts to appear. With some more rules and different distances, other fractals are achieved (see examples below).

[Live Demo](https://apidcloud.github.io/chaos-game/)

<img src="pictures/screenshot.png?raw=true">

<img src="pictures/cover-all.png?raw=true">
