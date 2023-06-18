# Mushroom-Classification

## Abstract

This study focuses on the classification of mushrooms into two categories, namely Poisonous and Edible, using a machine learning model. It aims to determine the significant features that play a crucial role in predicting the edibility or toxicity of mushrooms. Mushrooms have been consumed since ancient times and are highly regarded for their nutritional value. They are low in calories, carbohydrates, fats, and sodium, while being cholesterol-free. Mushrooms offer essential nutrients such as selenium, potassium, riboflavin, niacin, Vitamin D, proteins, and fiber. They have a rich history as a food source and are also recognized for their healing properties in traditional medicine. Various health benefits and potential disease treatments have been associated with mushrooms, including their anticancer and antitumor properties. Moreover, mushrooms exhibit antibacterial effects, enhance the immune system, and assist in lowering cholesterol levels. Furthermore, mushrooms are a valuable source of bioactive compounds. Throughout this machine learning analysis, we will identify the key features that determine whether a mushroom is poisonous or edible.

## How to use?

You can observe that the characteristics of the mushroom need to be selected using the provided dropdown menus for each input field. For the example mentioned, the following selections were made:

Cap-Surface: 

Bruises: 

Gill-Spacing:

Gill-Size: 

Gill-Color: 

Stalk-Root:

Stalk-Surface-Above-Ring: 

Stalk-Surface-Below-Ring: 

Ring-Type:

Spore-Print-Color: 

Population: 

Habitat: 

Once all the input fields have been selected, you simply need to click on the "Submit" button, which will lead you to the results page.

## Summary

1. The distribution of the target classes in our data is relatively balanced, with 3916 instances of the "poisonous" class and 4208 instances of the "edible" class, indicating an equal representation of both classes.

2. Among the four types of cap surfaces in mushrooms, our data suggests that "edible" mushrooms do not have the cap surface characterized by "grooves" (denoted as 'g').

3. The presence or absence of bruises on a mushroom does not determine its edibility according to our data, as both "poisonous" and "edible" mushrooms can exhibit bruising.

4. The gill spacing of a mushroom, whether close or crowded, does not provide a definitive indication of its edibility, as both "poisonous" and "edible" mushrooms can have either gill spacing.

5. The gill size of a mushroom, whether narrow or broad, does not serve as a conclusive factor in determining its edibility, as both "poisonous" and "edible" mushrooms can exhibit either gill size.

6. Our data indicates that "edible" mushrooms do not possess gill colors classified as "Buff" or "Green," while "poisonous" mushrooms do not have gill color described as "Red" or "Orange."

7. Among the various types of stalk root in mushrooms, the "Rooted" type is not associated with "poisonous" mushrooms according to our data.

8. The stalk surface above the ring of a mushroom can be classified as "Smooth," "Fibrous," "Silky," or "Scaly" without providing a definite indication of its edibility, as both "poisonous" and "edible" mushrooms can have any of these surface types.

9. Similarly, the stalk surface below the ring of a mushroom can be categorized as "Smooth," "Fibrous," "Silky," or "Scaly" without reliably determining its edibility, as both "poisonous" and "edible" mushrooms can exhibit any of these surface types.

10. Our data reveals that "edible" mushrooms do not possess ring types classified as "Large" or "None," while "poisonous" mushrooms do not have a ring type described as "Flaring."

11. The spore print color of a mushroom does not serve as a definitive factor in determining its edibility, as our data indicates that "edible" mushrooms do not have spore print color described as "Green," while "poisonous" mushrooms do not possess spore print colors described as "Purple," "Orange," "Yellow," or "Buff."

12. According to our data, "poisonous" mushrooms are not associated with population types described as "Numerous" or "Abundant."

13. The habitat type of a mushroom does not reliably indicate its edibility, as our data suggests that "poisonous" mushrooms are not found in waste habitats.

14. The XGBoost Classifier model achieves 100% accuracy on both the training and test data.





