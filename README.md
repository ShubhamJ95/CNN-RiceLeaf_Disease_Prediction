# CNN-RiceLeaf_Disease_Prediction
"The dataset contains images of rice leaf. There are three classes/diseases: Bacterial leaf blight, Brown spot, and Leaf smut, each having 40 images. The format of all images are jpg. "

# Problem Statement
Task 1:-Prepare a complete data analysis report on the given data.

Task 2:-Create a model which can classify the three major attacking diseases of rice plants like leaf blast, bacterial blight and brown spot.

Task3:- Analyze various techniques like Data Augmentation, etc and create a report on that.

-----------------------------------------------------------------------------------------------------------------------------------------------------

The image datasets consist of 3 classes, namely Bacterial leaf blight, Brown spot and leaf smut. Each classes contain 40 image data except for leaf smut with 39 image data.

1) Bacterial leaf blight : Bacterial leaf blight of rice is a very dangerous disease that can cause significant damage to rice crops. It is caused by the bacterium Xanthomonas oryzae pv. oryzae and is one of the most serious diseases of rice. The disease causes wilting of seedlings and yellowing and drying of leaves. It is most likely to develop in areas that have weeds and stubbles of infected plants, and it can occur in both tropical and temperate environments, particularly in irrigated and rainfed lowland areas. The disease favors temperatures at 25−34°C, with relative humidity above 70%. The earlier the disease occurs, the higher the yield loss. Yield loss due to bacterial blight can be as much as 70% when susceptible varieties are grown, in environments favorable to the disease

2) Brown spot : Brown spot is a fungal disease that infects the coleoptile, leaves, leaf sheath, panicle branches, glumes, and spikelets of rice plants1.It is a fungal issue, caused by Bipolaris oryzae (previously known as Helminthosporium oryzae). Its most observable damage is the numerous big spots on the leaves which can kill the whole leaf. When infection occurs in the seed, unfilled grains or spotted or discolored seeds are formed. Brown spots on rice can start on even seedling leaves and are usually small, round to oval circles, brownish in color. As the crop grows, leaf spots may change colors and vary in shape and size, but are usually round. The disease can develop in areas with high relative humidity (86−100%) and temperature between 16 and 36°C. It is common in unflooded and nutrient-deficient soil, or in soils that accumulate toxic substances. For infection to occur, the leaves must be wet for 8−24 hours. The fungus can survive in the seed for more than four years and can spread from plant to plant through air.

3) Leaf Smut : Leaf smut is a fungal disease caused by Entyloma oryzae that affects rice crops. The fungus produces slightly raised, angular, black spots (sori) on both sides of the leaves. Although rare, it also can produce spots on leaf sheaths. The characteristic sign of rice with leaf smut is the presence of small black spots on the leaves. They are slightly raised and angular and give the leaves the appearance of having been sprinkled with ground pepper. Coverage by these spots is most complete on the oldest leaves. The tips of some leaves with the most infection may die. It is widespread where rice is grown, but leaf smut doesn’t often cause serious damage.
 
-----------------------------------------------------------------------------------------------------------------------------------------------------
# Summary
In this project, we managed to classify images of rice leaf diseases using a tf.keras.Sequential model and load data using tf.keras.utils.image_dataset_from_directory. It demonstrates the concepts of efficiently loading a dataset off disk and identifying overfitting and applying techniques to mitigate it, including data augmentation and dropout. Our basic machine learning workflow are:

Examine and understand data
Build an input pipeline
Build the model
Train the model
Test the model
