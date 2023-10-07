# AGRIMETRICS 🌿

A simple ML and DL based website which recommends the best crop to grow, fertilizers to use and the diseases caught by your crops.

# MOTIVATION 💪

* Farming is one of the major sectors that influences a country’s economic growth.

* In country like India, majority of the population is dependent on agriculture for their livelihood. Many new technologies, such as Machine Learning and Deep Learning, are being implemented into agriculture so that it is easier for farmers to grow and maximize their yield.

* In this project, I present a website in which the following applications are implemented; Crop recommendation, Fertilizer recommendation and Plant disease prediction, respectively.

* In the crop recommendation application, the user can provide the soil data from their side and the application will predict which crop should the user grow.

* For the fertilizer recommendation application, the user can input the soil data and the type of crop they are growing, and the application will predict what the soil lacks or has excess of and will recommend improvements.

* For the last application, that is the plant disease prediction application, the user can input an image of a diseased plant leaf, and the application will predict what disease it is and will also give a little background about the disease and suggestions to cure it.

# How to use 💻

* Crop Recommendation system ==> enter the corresponding nutrient values of your soil, state and city. Note that, the N-P-K (Nitrogen-Phosphorous-Pottasium) values to be entered should be the ratio between them. Refer this website for more information. Note: When you enter the city name, make sure to enter mostly common city names. Remote cities/towns may not be available in the Weather API from where humidity, temperature data is fetched.

* Fertilizer suggestion system ==> Enter the nutrient contents of your soil and the crop you want to grow. The algorithm will tell which nutrient the soil has excess of or lacks. Accordingly, it will give suggestions for buying fertilizers.

# How to run locally 🛠️

* Before the following steps make sure you have git, Anaconda or miniconda installed on your system

* Clone the complete project with git clone https://github.com/Rushi-Balapure/Agrimetrics.git or you can just download the code and unzip it

* Once the project is cloned, open anaconda prompt in the directory where the project was cloned and paste the following block

conda create -n harvestify python=3.6.12
conda activate harvestify
pip install -r requirements.txt

* And finally run the project with
 python app.py
* Open the localhost url provided after running app.py and now you can use the project locally in your web browser.
