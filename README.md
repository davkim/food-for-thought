# food-for-thought
Machine learning project to identify the name of the food by image



Simple high level architecture design plan of food-for-thought

1. Data Collection (training data)

 - Write python (probably use selenium) to collect food images from Google -- all images should obviously be tagged with their name (also it would be good to add
the country which it is from - this would aid in the image search when the English translation of the name is too generic. e.g. 东坡肉 - braised pork on wikipedia)

 - List of food can be possibly be found on wikipedia (e.g. https://en.wikipedia.org/wiki/List_of_Chinese_dishes)

2. Data Processing 

 - Turn image into some sort of data type that could easily be used with existing ML algo/apis - some sort of image vectorizor?

 - discard unusuable data - e.g. file size too big, or cannot fit with the image vectorizor

3. Train the model 

 - Run ML algorithm to map image data to the name of the food.

