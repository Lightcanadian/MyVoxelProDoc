# Generation Tips And Trick

## Single Island/Continent
Source: [Voxel Plugin Discord](https://discord.com/channels/379297529235243020/607761275333902338/806846988502171699)
### Focal point
You can use the vector length to determine the center location of the map

|Setup|Output|
|-----|------|
|<img src="GenerationImages/2021-04-24-10_47_13-Window.png" alt="Image" width="200"/>|<img src="GenerationImages/2021-04-24-10_47_46-Window.png" alt="Image" width="200"/>|

### Control the size
This is however not useable since the length that is returned is larger than 1. If you were to generate with just this, you would get a spike from the center that goes up to infinity.
In order to make it useable, we need to device the return value until it's whithin range of useafull generation.

|Setup|Output|
|-----|------|
|<img src="GenerationImages/2021-04-24-11_07_06-Window.png" alt="Image" width="200"/>|<img src="GenerationImages/2021-04-24-11_08_08-Window.png" alt="Image" width="200"/>|

### Deform
Since the previous steps create a perfect circle, we can add some noise to deform the circle

|Setup|Output|
|-----|------|
|<img src="GenerationImages/2021-04-24-11_22_11-Window.png" alt="Image" width="200"/>|<img src="GenerationImages/2021-04-24-11_24_06-Window.png" alt="Image" width="200"/>|

### Populate the Island
You can then use this information to populat the island data with a simple lerp float.

|Setup|Output|
|-----|------|
|<img src="GenerationImages/2021-04-24-11_13_30-Window.png" alt="Image" width="200"/>|<img src="GenerationImages/2021-04-24-11_25_04-Window.png" alt="Image" width="200"/>|

> NOTE: This current setup will have plains at sea level where it should be ocean. The B value of the lerp can be change to a value bolow 0 to at least be under the sea level if need be.