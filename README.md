# Project: OCR (Optical Character Recognition) 

![image](figs/intro.png)

### [Full Project Description](doc/project4_desc.md)

Term: Fall 2018

+ Team #2
+ Team members
	+ Ghada Jerfel 
	+ Peilin Li
	+ Xiaoyi Li
	+ Hengyang Lin
	+ Zhibo Zhou

+ Project summary: In this project, we created an OCR post-processing procedure to enhance Tesseract OCR output. There are four parts in our project. The first one is data cleaning, we removed punctuation and numbers for each file， then we compared with ground-truth by rows. The second part is error detection；there are 8 rules that we used as our algorithm based on paper D1 section 2.2. The third part is error correction. Here，we first propose candidates for correct words, next we compute a score for each candidate, and last we correct the word with the one that has the highest scores. The final step is performance measurement.
![screenshot](doc/project4.png)
	
**Contribution statement**: 
+ Project Leader：
  + Hengyang Lin: Designed and organized the structure of the whole project. Built "Error detection" part and "Error correction" part. Searched different kinds of papers that relate to this project.
  
+ Major contributor:
  + Zhibo Zhou : Designed and wrote "Error Detection" part and "Data cleaning" part. Searched different kinds of papers that       relate to this project and prepared the presentation.
  + Peilin Li : Designed and wrote "Error Detection" part and "Data cleaning" part. Searched different kinds of papers relating to those two parts. 
  
+ Equal contribution：
  + Ghada Jerfel : Designed and wrote "Performance Measurement" and edited the readme file.
  + Xiaoyi Li: Designed and wrote "Performance Measurement" and edited the readme file.
  


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
