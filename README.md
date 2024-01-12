# **Crop Prediction**

-----------------------------

## **Business Case-Study**

Machine Learning is well equipped when it comes to analyzing data regarding soil conditions, including moisture level, temperature, and chemical makeup, all of which have an impact upon crop growth and livestock well-being.
Today in agriculture, this can allow crops to be grown at much higher precision, enabling farmers to treat plants and animals almost individually, which in turn significantly increases the effectiveness of farmers' decisions.
Using this can develop means to even predict harvest yields and evaluate crop quality for individual plant species to detect crop disease and weed infestations which were previouly impossible!

------------

## **Dataset Description**

This Dataset have 7 features and 1 target (label)

1) N : Nitrogen Content of soil in ppm. It promotes leafy, vegetative growth and is vital for the overall development of plants.

2) P : Phosphorus Content of soil in ppm. It supports root development, flowering, and fruiting.

3) K : Potassium Content of soil in ppm. It enhances overall plant vigor, helps in disease resistance, and contributes to the quality of fruits.

4) Temperature : Temperature influences the metabolic processes in plants.

5) Humidity : It affects transpiration in plants, influencing water uptake and loss.

6) pH : It influences nutrient availability to plants. Different crops have specific pH preferences, and adjusting soil pH can impact nutrient absorption.

7) Rainfall : It is crucial for providing water to plants. Adequate rainfall is essential for crop growth, and the amount needed varies among different crops.

8) Label : Types of Crop ('rice', 'maize', 'chickpea', 'kidneybeans', 'pigeonpeas', 'mothbeans', 'mungbean', 'blackgram', 'lentil','pomegranate', 'banana', 'mango', 'grapes', 'watermelon', 'muskmelon', 'apple', 'orange', 'papaya', 'coconut', 'cotton', 'jute', 'coffee').

---------------

### **Graphical Analysis**

![image](https://github.com/Bamit-2021/Crop-Prediction/assets/77608956/adedb16d-bb0d-4c9c-bf11-bbd7c59994a6)

![image](https://github.com/Bamit-2021/Crop-Prediction/assets/77608956/801a45b4-25d6-4e95-b34b-6bd9ad928ecd)

![image](https://github.com/Bamit-2021/Crop-Prediction/assets/77608956/dffc173c-33b6-4d1d-97a9-eca78e7b5f29)


-----------

### **Analysis from Graphs**

1) We cannot consider outliers as an outliers since some crop have high or low feature values.

2) Grapes and apple need high value of Potassium and Phosphorus from bar graph. 

3) We can analyse that chikpeas and kidneybeans need low himidity as below 20.

4) We analyse that rice need rainfall upto 250 while muskmelon need rainfall below 50.

5) Most crops need pH value range from 5 to 8 based on the scatterplot.

------------

## **Model Comparison Report**:

```
+---------------+-----------------------+-----------------+
| Model Name    |   Testing Accuracy(%) | Ranking order   |
+===============+=======================+=================+
| Random Forest |               98.9091 | 1st             |
+---------------+-----------------------+-----------------+
| Decision Tree |               98.3636 | 2nd             |
+---------------+-----------------------+-----------------+

```
-------------

For More Information Please review the full analysis in the [Crop_Prediction.ipynb](https://github.com/Bamit-2021/Crop-Prediction/blob/main/Crop_Prediction.ipynb).

For any additional questions, feel free to email me at patroamit358@gmail.com
