# Calorie (Android)

# Team Member  (Team #25: 4PTC)
| Name | ID | Email |
|------|----|-------|
|Xiong, Jiabin|57178186|jiabinx@uci.edu|
|Zhou, Yingchen|55879895|yingcz1@uci.edu|
|Hua, Xinjin|88917395|xinjinh1@uci.edu|
|Ye, Jiawen|54035818|jiaweny7@uci.edu|

## TODO
- [x] Presentation Slide
- [x] Source code
- [x] Video
- [ ] Demo

## Assignment
* Slides: CS125-Final Presentation.pptx
* Source code: Version_Mar8_10.46_Calories.zip
* Presentation: CS125 Presentation.mp4



## External Libraries
1. <a href = https://github.com/jjoe64/GraphView>GraphView</a> -> For displaying the plot of weights
2. Okhttp -> For connecting to APIs
3. <a href = https://github.com/bumptech/glide>Glide</a> -> For loading online image

## External Sources
1. <a href = https://www.iconfont.cn>Images source</a> that we use as buttons
2. <a href = https://www.jb51.net/article/133617.htm>The animation of progress bar</a>

## Backend and Data Storage
* <a href = "https://www.bmob.cn/">Bmob</a>
* Shared Preference

## APIs

| API | What it can do |
|-----|----------------|
|<a href = https://rapidapi.com/edamam/api/edamam-food-and-grocery-database>edamam</a>|Food database|
|<a href = https://rapidapi.com/spoonacular/api/recipe-food-nutrition?>Spoonacular</a>|Recipe according to any nutirtion needs|

## Other API Options
* <a href = https://rapidapi.com/calorieninjas/api/calorieninjas>CalorieNinjas</a>

## Calculate BMR and Daily Intake
1. <a href = https://www.diabetes.co.uk/bmr-calculator.html>BMR (Suggested Daily Calories)</a>
  * BMR for Men = 66.47 + (13.75 * weight [kg]) + (5.003 * size [cm]) − (6.755 * age [years])
  * BMR for Women = 655.1 + (9.563 * weight [kg]) + (1.85 * size [cm]) − (4.676 * age [years])
2. <a href = https://diabetesstrong.com/how-much-protein-carbs-fat-should-you-eat/>Daily Intake (40/40/20 Principle)</a>
  * Eg. Daily Suggested Calories = 2000 Cal
  * 2000 * 0.4 calories from protein / 4 = 200 g Protein
  * 2000 * 0.4 calories from carbs / 4 = 200 g carbs
  * 2000 * 0.2 calories from fat / 9 = 45 g fat
