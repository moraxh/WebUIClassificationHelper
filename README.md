# WebUIClassificationHelper®

Helper for the classification of sentiments of comments saved in CSV for a research project at the University of Guanajuato

# Installation

```sh
# Cloning Repository
git clone https://github.com/moraxh/WebUIClassificationHelper.git

# Changing Directory
cd ClassificationUIHelper

# Open index.html
```

# Improvements In Time
Up to 40% improvement in classification speed
![](pictures/graph.png)

# Example Usages
![](pictures/screenshot.png)

input.csv
```csv
20,2022-06-13 20:48:15,dummy
21,2022-06-07 18:43:37,test
22,2022-06-07 12:44:07,😂😂😂😂😂
23,2022-06-07 12:24:10,😅
24,2022-06-11 13:52:39,why are you reading this?
```

input_classified.csv
```csv
0,dummy,2
1,test,0
2,😂😂😂😂😂,1
3,😅,1
4,why are you reading this?,0
```

# License
This project is licensed under the [MIT License](LICENSE).