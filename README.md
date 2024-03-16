[Yale University, Rothberg Fund (2020), USA](https://medium.com/tsai-city/kickstarting-healthcare-innovation-with-the-rothberg-catalyzer-prototype-fund-6f5a1f37c5c2): [“CHEST-AI: AI tool for detection of lung diseases from chest X- ray data”,](https://www.chestai.org/) , Role: Investigator. Github Poster Link [*2023:1, 4, 9; 2021: 17, 23][**21, 23, 29, 30]

[Entrepreneurship Foundation Fund (2020), USA](https://www.entrepreneurshipfoundation.org/): “CHEST-AI: AI tool for detection of lung diseases from chest X- ray data”, [Github](https://www.chestai.org/) , Role: Investigator. [*2023:1, 4, 9; 2021: 17, 23] [**21, 23, 29, 30]

[Culinda Technologies (2020), Texas, USA](https://www.culinda.io/): Machine learning solutions for medical devices that provide deep insight into IoT and IoMT applications, Angel investment, Github Role: Investigator. [*2023:1, 4, 9; 2021: 17, 23] [**21, 23, 29, 30]
<img width="1433" alt="ChestAi" src="https://github.com/spawar2/Chest-X-ray-Neural-Nets/assets/25118302/eec7c627-7c54-4677-b7b1-db210ec7fa16">


# ChestAI [APP](http://20.169.253.49:5001/login)

[Product:](https://aws.amazon.com/marketplace/seller-profile?id=seller-b6otd3wry7lkk)

## Currently working on training diverse classifiers to create a strong ensemble

## Single Model avg AUC score for SOTA paper 0.894

## Uncertainity Labels
U-Ones: Map all uncertain labels to positive

U-Zeros: Map all uncertain labels to negative

U-Mixed: Map uncertain labels to either positive or negative according to previous results

## Transforms
Rotation, Lighting, Warping

## Abbreviations 
FE: Feature Extraction

FT: Fine Tuning

score: Avg AUC Score

## Baseline U-Mixed (the best approach)
DenseNet121, WeightDecay, Dropout, One Cycle Policy, Transforms

model0: score(FE): 0.891; score(FT): **0.89**

model1(Mixed Precision): score(FE): **0.891**

model2: score(FE): 0.889

model3: score(FE): 0.882

ensemble of above 4 models: **0.895** (The increment is marginal owing to the similar architectures of models)

## Baseline U-Ones 
DenseNet121, WeightDecay, Dropout, One Cycle Policy, Transforms

score(FE): 0.87

## Baseline U-Zeros 
DenseNet121, WeightDecay, Dropout, One Cycle Policy, Transforms

score(FE): 0.875

## Progressive (doesn't help in our case)
DenseNet121, U-Mixed, WeightDecay, Dropout, One Cycle Policy, Transforms, scaled from 160 to 320 px

score(160px, FE):  0.878; score(160px, FT): 0.879; score(320px, FE): 0.887

## Label Smoothing (doesn't help in our case)
DenseNet121, U-Mixed, WeightDecay, Dropout, One Cycle Policy, Transforms, Mapped uncertain 0s to 0.2s and 1s to 0.8s

score(FE): 0.878

https://github.com/rushikeshchopaderc
https://in.linkedin.com/in/rushikesh-chopade-88470615b
https://github.com/SurajK7/
https://in.linkedin.com/in/surajkumar1004
This project in collaboration with Rushikesh Chopade, Suraj Kumar Undergraduate student: Indian Institute of Technology (IIT), Kharagpur, India. Project: CHEST-AI: AI tool for detection of lung diseases from chest X- ray data (Spring 2021). Paper Paper Paper Paper Paper 
https://link.springer.com/chapter/10.1007/978-981-19-9819-5_49
https://link.springer.com/chapter/10.1007/978-981-19-7660-5_7
https://www.researchsquare.com/article/rs-1129014/latest.pdf
https://www.biorxiv.org/content/10.1101/2021.09.21.461307v1.abstract
https://dl.acm.org/doi/abs/10.1145/3469213.3469214
http://20.169.253.49:5001/login
https://aws.amazon.com/marketplace/seller-profile?id=seller-b6otd3wry7lkk
https://bpb-us-w2.wpmucdn.com/campuspress.yale.edu/dist/7/3679/files/2023/10/ChestAi-300x167.png

## Regularization (doesn't help in our case)
DenseNet121, U-Mixed, One Cycle Policy, Transforms

score: NA

<img width="218" alt="CLR" src="https://github.com/spawar2/Chest-X-ray-Neural-Nets/assets/25118302/b5437360-9591-457c-beed-4d60519fba9e">

https://campuspress.yale.edu/shrikantpawar/files/2024/02/ICICT-2024-65f2cb2ed915354a.pdf
https://scepscor.org/adapt-in-sc-thrust-2/
https://www.sc-bdhs-conference.org/agenda2024/
https://campuspress.yale.edu/shrikantpawar/files/2024/01/USC-BigData-2024-2b5a6615672cd9bd.pptx
https://link.springer.com/chapter/10.1007/978-3-031-34960-7_23
https://campuspress.yale.edu/shrikantpawar/files/2024/01/USC-BigData-Poster-ea9b620665de21e0-rotated-e1706728883865-225x300.jpg
 https://iwbbio.ugr.es/
https://www.claflin-computation.com/_files/ugd/81dd80_82ed579c7718410ab538e1fecbd85714.pdf
https://youtu.be/988lbQ4ekao
https://www.claflin-computation.com/lab-journey?pgid=ktmii98q-5ec312bd-56e6-4010-98de-91e7af6dcc55
https://link.springer.com/chapter/10.1007/978-3-031-34960-7_23
http://20.169.253.49:5001/login
https://github.com/spawar2/Chest-X-ray-Neural-Nets
https://ventures.yale.edu/yaleinnovationsummit
1	9th International Congress on Information and Communication Technology (ICICT 2024) London, United Kingdom, Addressing Class Imbalance Problem in Semantic Segmentation using Binary Focal Loss, Rushikesh Chopade, Aditya Stanam, & Shrikant Pawar. https://sched.co/1a1eC (NSF RII Track-1 award funded project)
1	5th National Big Data Health Science Conference (2024), University of South Carolina, Columbia, Cyclical Learning Rates (CLR’S) for Improving Training Accuracies and Lowering Computational Cost, Rushikesh Chopade, Aditya Stanam, Anand Narayanan & Shrikant Pawar Poster Paper Poster (NSF RII Track-1 award funded project) GitHub 
1	10th International Work-Conference on Bioinformatics and Biomedical Engineering, Gran Canaria, Spain, 2023. Cyclical Learning Rates (CLR’s) for Improving Training Accuracies and Lowering Computational Cost. Poster Presentation CertificateApp.        Paper Product (NSF RII Track-1 award funded project) GitHub 
Yale Innovation Summit 2022, Eposter: Application of neural networks for aiding lung diagnosis of lung disorders, by Pawar S.D, R. Chopade and A. Stanam, https://ventures.yale.edu/yaleinnovationsummit Product
![image](https://github.com/spawar2/Chest-X-ray-Neural-Nets/assets/25118302/79ca835e-15ae-4f45-a89e-f6880416ed60)
![USC Research Core Fair 1 2024](https://github.com/spawar2/Chest-X-ray-Neural-Nets/assets/25118302/f23ed29d-a433-4e64-b114-19886eccbd42)
2024 University of South Carolina 2nd Annual Research Core Fair, Columbia, Cyclical Learning Rates (CLR’S) for Improving Training Accuracies and Lowering Computational Cost, Rushikesh Chopade, Aditya Stanam, Anand Narayanan & Shrikant Pawar Poster Paper Product (NSF RII Track-1 award funded project) GitHub
https://campuspress.yale.edu/shrikantpawar/files/2024/03/Research-Core-Fair-2024-submitted-abstracts-163910a83f12c05b.pdf
https://link.springer.com/chapter/10.1007/978-3-031-34960-7_23
https://github.com/spawar2/Chest-X-ray-Neural-Nets
https://scepscor.org/adapt-in-sc-thrust-2/
https://sc.edu/about/offices_and_divisions/research/news_and_pubs/news/2024/20240109_2024ResearchCoreFair_Announcement.php
(NSF RII Track-1 award funded project): https://scepscor.org/adapt-in-sc-thrust-2/


