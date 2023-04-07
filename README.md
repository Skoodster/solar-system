# 2D solar-system
css practice with a healthy serving of math

https://user-images.githubusercontent.com/121529529/230516003-9f6a8323-0845-4d18-99d9-1fedcf2e4ebc.mp4

----------------------------------------------------------------

## Planets
Mercury ![image](https://user-images.githubusercontent.com/121529529/230512579-1f939ab9-e420-42b5-877a-0121be6e09b3.png)

Venus ![image](https://user-images.githubusercontent.com/121529529/230512598-9d4c3e8e-919f-4e9c-bd90-6657b23f97c8.png)

Earth ![image](https://user-images.githubusercontent.com/121529529/230512662-efceed0e-f2c8-40df-8209-c23f38251cfb.png)

Mars ![image](https://user-images.githubusercontent.com/121529529/230512708-68af74fa-5d71-4f33-8c6e-b28847da2afb.png)

Jupiter ![image](https://user-images.githubusercontent.com/121529529/230512747-13e6fa81-3e85-4671-bd4e-095c03b7e863.png)

Saturn ![image](https://user-images.githubusercontent.com/121529529/230512767-0c404b10-7aeb-4c7b-96d6-aa1e7c9dc166.png)

Uranus ![image](https://user-images.githubusercontent.com/121529529/230512778-fea815c9-266f-41a4-85f1-4703fc773df3.png)

Neptune ![image](https://user-images.githubusercontent.com/121529529/230512798-a45fd03b-6478-46fe-9f6d-2790cca207b9.png)

----------------------------------------------------------------

## The Math
- Determine length of each planet's year in Earth days
- Convert days to seconds
- Determine orbit duration for each planet -> (length of each planet's year in seconds) / (length of Earth year in seconds)
```
Earth orbit duration = 1 second
1 Earth year = 31,557,600 seconds
Mars year ≈ 687 Earth days
687 Earth days = 5.94 x 10^7 seconds
((5.94 x 10^7 seconds)/(31,557,600)) * 1 = 1.88 seconds
Mars orbit duration = 1.88 seconds
```

Orbit duration data acquired from [NASA](https://www.nasa.gov)

----------------------------------------------------------------

## TODO

- [ ] Make distance from the Sun proportional to real life distance from the Sun using equation derived from Kepler's 3rd Law of Planetary Motion

Kepler's equation where:

T = Planet year in seconds, G = Gravitational constant (6.6743 × 10-¹ m³ kg-¹ s-²), M = Mass of the Sun (1.9891 × 10³°kg), and 
a = average distance from the Sun:
```
T² = (4π²/GM) x a³
```
Derived equation to solve for a:
```
a = [(GM x T²)/(4π²)]^(1/3)
```

- [ ] Make size of planets proportional to their real life size
