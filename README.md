# Car model classifier with datasets which we made from Various View Point Image.

## Goal
Implement model that can classify specific vehicle
<br>

## Datasets
- Images from sites google
- We used only front side of cars
- Additionally, we tried two parts of car(whole part & front grill) to compare which data is the best.
- The point of our project is that image we made from Various View Point image was used.
- We used 3 classes(Audi, Benz, Grandeur), Each class has 250 image(train : 200, test : 50).


## Various View Point Image(increasing number of images)
1. Get the front grilles(& whole images) from vehicle images which is clear and have no noise.
2. Distortion these image just like side view of the vehicles using control points of image.
(Only front part of the car)
3. Set a degree of viewpoint depending on how many images you want to generate.
4. Save those distorted images for the dataset.
5. Repeat 1~4 on each class(3 classes(models) in my case)


## Deep Learning
- Deep Learning, CNN.
- We chose 'Keras' for CNN tools because it Allows for easy and fast prototyping. <a href = 'https://keras.io/'>Keras Documentation</a>
- We made CNN model suitable for our datasets by changing the size of various hidden layer structures and filters.
<hr>

