# Sixty Nautical Miles per Degree on Flat Earth

## Content

- [Introduction](#introduction)
	- [GP and Zenith](#gp-and-zenith)
	- [60 NM per Degree](#60-nm-per-degree)
	- [The Trigonometry Problem on Flat Earth](#the-trigonometry-problem-on-flat-earth)
	- [Four Points](#four-points)
- [The Data](#the-data)

## Introduction

In this document we'll look at how a simple rule used in celestial navigation debunks the idea that Earth could be flat.

### GP and Zenith

The position on Earth where a star appears overhead is called the geographical position (GP) of that star. Another key concept here is the name of this point directly overhead, it is called **Zenith**.

### 60 NM per Degree

It is a rule of thumb that the distance between an observer and the GP of a star correlates to how high in the sky the star is for that observer, and that correlation is understood to be 60 nautical miles (NM) per degree.

For example, let's say the star Betelgeuse is directly overhead (at the zenith of) an observer, that means that observer is standing on Betelgeuse's GP. At the same time a second observer sights Betelgeuse, but for him the star is 30° below his zenith. Using the rule of thumb the distance between these two observers would be $60 \times 30 = 1800$ NM. If another observer has the star 60° below his zenith, then this third observer would be $60 \times 60 = 3600$ NM away from the star's GP and so on.

### The Trigonometry Problem on Flat Earth

If you're familiar with trigonometry you might already be spotting an issue for flat Earth with this correlation. We can use trigonometric functions to figure out, for example, how high the top of a building will appear for an observer giving the building's height, the observer's height and the distance between the observer and the building. And for the top of the building to drop from 30° to 60° by simply moving away from it over a flat surface it would require you to triple your distance to the building, while with the rule of thumb of navigation the distance is just doubling.

There are, however, ad-hoc hypotheses that could explain how this 60 NM per degree relationship could emerge on flat Earth, with some type of upward light bending or some other sort of idea. The goal of this document is not to explore this argument, we will simply accept the rule and assume there is some mechanism that explains it or causes it on flat Earth and move forward.

### Four Points

There is still a deeper problem to be explored, because this relationship can provide us with long distances between points on Earth's surface, and again, with the help of geometry or with scaled down models, we can determine whether this distances could or could not exist within a flat surface.

If it's not clear that with distances between points it's possible to rule out they being on a plane, try picturing four points on the same plane that have the same distance between all pairs of points. If you immediately thought of a square, notice that the four pairs of adjacent points forming the sides of the square are equidistant, however opposing points that form diagonals in this square are at a larger distance apart, around 41.4% larger.

There are six pairs of points in a group of four points. And it's not possible to have all six pairs equidistant when the points are in the same plane.

If you're now wondering if a curved surface could solve that, it turns out it can. You can play with a 3D example of it [here](https://www.geogebra.org/m/m6A6U95q). Or just check the Image below.

![Sphere with four equidistant points](img/sphere-4-points.png)

## The Data

Four cities were picked for this experiment: Tres Marias (Mexico), Saint-Constant (Canada), Jaboatão dos Guararapes (Brazil) and Cuiabá (Brazil). Three of them are in the path of the GP of a navigation star. So for around half the year those cities every night at some point become the GP of their respective stars, allowing other observers to get their distance to it by simply measuring the angle to that star. The fourth city, Cuiabá, isn't in the path of a navigation star, but from that city the other stars can be observed when their GPs are over the target cities.

Here are the coordinates considered for each city:
- **Tres Marias:** N 19° 3' 7.40", W 99° 14' 33.50"
- **Saint-Constant:** N 45° 22' 1.40", W 73° 34' 55.50"
- **Jaboatão:** S 8° 10' 20.70", W 34° 54' 54.40"
- **Cuiabá:** S 15° 36' 35.70", W 56° 3' 58.40"

Taking the actual measurements would require some effort and resources, either finding volunteers that have access to the given locations or paying professionals to do it. Still doable. But so far I'll resort to a free and open source software that can render how the sky is observed from any given location and time with high accuracy, which is [Stellarium](https://stellarium.org/).

Setting the time for UTC 8:05:10 AM April 3rd, 2024 we get that the Star arcturus is overhead Tres Marias. At that same time, Arcturus is observed to be at the altitude angles `56° 12'` from Saint-Constant and `35° 11' 46.4"` from Cuiabá.

At 5:34:45 AM, July 22nd, 2024, the star Deneb is over Saint-Constant, and its altitude angles are `26° 15' 14.1"` from Jaboatão and `27° 01' 09.9"` from Cuiabá.

<!-- 
- name: Tres Marias - Mexico
- GP: N 19° 3' 7.40", W 99° 14' 33.50"
- time: 2024-04-03 08:05:10
- star: Arcturus

- name: Saint-Constant - Canada
- GP: N 45° 22' 1.40", W 73° 34' 55.50"
- time: 2024-07-22 05:34:45
- star: Deneb

- name: Jaboatão dos Guararapes - Brazil
- GP: S 8° 10' 20.70", W 34° 54' 54.40"
- time: 2024-12-21 01:34:56
- star: Rigel

- name: Cuiabá - Brazil
- GP: S 15° 36' 35.70", W 56° 3' 58.40"

- Saint-Constant to Tres Marias: 56° 12' 00.0"
- Cuiabá to Tres Marias:         35° 11' 46.4"
- Jaboatão to Saint-Constant:    26° 15' 14.1"
- Cuiabá to Saint-Constant:      27° 01' 09.9"
- Cuiabá to Jaboatão:            68° 02' 02.6"
- Tres Marias to Jaboatão:       21° 04' 38.9"
-->
