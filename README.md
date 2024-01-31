# Sampling-Normal-and-Binomial-Distributions-Problem-Set
Week 3 tasks on Normal and Binomial distribution

Week 2, Task
Sandra Nwankwo
2024-01-29
Abstract

Importance There are racial inequities in health care access and quality in the United States. It is unknown whether such differences for racial and ethnic minority beneficiaries differ between Medicare Advantage and traditional Medicare or whether access and quality are better for minority beneficiaries in 1 of the 2 programs.

Objective:To compare differences in rates of enrollment, ambulatory care access, and ambulatory care quality by race and ethnicity in Medicare Advantage vs traditional Medicare.

Design, Setting, and Participants: Exploratory observational cohort study of a nationally representative sample of 45 833 person-years (26 887 persons) in the Medicare Current Beneficiary Survey from 2015 to 2018, comparing differences in program enrollment and measures of access and quality by race and ethnicity.

Exposures: Minority race and ethnicity (Black, Hispanic, Native American, or Asian/Pacific Islander) vs White or multiracial; Medicare Advantage vs traditional Medicare enrollment.

Main Outcomes and Measures: Six patient-reported measures of ambulatory care access (whether a beneficiary had a usual source of care in the past year, had a primary care clinician usual source of care, or had a specialist visit) and quality (influenza vaccination, pneumonia vaccination, and colon cancer screening).

Results: The final sample included 6023 persons (mean age, 68.9 [SD, 12.6] years; 57.3% women) from minority groups and 20 864 persons (mean age, 71.9 [SD, 10.8] years; 54.9% women) from White or multiracial groups, who accounted for 9816 and 36 017 person-years, respectively.

Comparing Medicare Advantage vs traditional Medicare among minority beneficiaries, those in Medicare Advantage had significantly better rates of access to a primary care clinician usual source of care (79.1% vs 72.5%; adjusted marginal difference, 4.0%; 95% CI, 1.0%-6.9%), influenza vaccinations (67.3% vs 63.0%; adjusted marginal difference, 5.2%; 95% CI, 1.9%-8.5%), pneumonia vaccinations (70.7% vs 64.6%; adjusted marginal difference, 6.1%; 95% CI, 2.7%-9.4%), and colon cancer screenings (69.4% vs 61.1%; adjusted marginal difference, 7.1%; 95% CI, 3.8%-10.3%).

Comparing minority vs White or multiracial beneficiaries across both programs, minority beneficiaries had significantly lower rates of access to a primary care clinician usual source of care (adjusted marginal difference, 4.7%; 95% CI, 2.5%-6.8%), specialist visits (adjusted marginal difference, 10.8%; 95% CI, 8.3%-13.3%), influenza vaccinations (adjusted marginal difference, 4.3%; 95% CI, 1.2%-7.4%), and pneumonia vaccinations (adjusted marginal difference, 6.4%; 95% CI, 3.9%-9.0%). The interaction of race and ethnicity with insurance type was not statistically significant for any of the 6 outcome measures.

Conclusions and Relevance: In this exploratory study of Medicare beneficiaries in 2015-2018, enrollment in Medicare Advantage vs traditional Medicare was significantly associated with better outcomes for access and quality among minority beneficiaries; however, minority beneficiaries were significantly more likely to experience worse outcomes for most access and quality measures than White or multiracial beneficiaries in both programs.

TASKS

Research question (including the population of interest): How do Medicare beneficiaries of different races and ethnicities (P) in the United States experience care access and quality (O) in Medicare Advantage and traditional advantage (C) from 2015 to 2018 (T)?

Sampling method: Stratified Random Sampling

Sample description: In the Medicare current beneficiary survey from 2015 to 2018, a sample of 6023 persons (mean age, 68.9 [SD, 12.6] years; 57.3% women) from minority groups and 20 864 persons (mean age, 71.9 [SD, 10.8] years; 54.9% women) from White or multiracial groups was obtained from a population of 45 833 (9816 Minority and 36 017 White/Multiracial)

Primary outcome: Ambulatory care access and ambulatory care quality

Citation: Giesinger, K., Hamilton, D. F., Erschbamer, M., Jost, B., & Giesinger, J. M. (2015). Black medicine: an observational study of doctors’ coffee purchasing patterns at work. BMJ, 351.

Abstract Objective To evaluate doctors’ coffee consumption at work and differences between specialties.

Design Single centre retrospective cohort study. Setting Large teaching hospital in Switzerland.

Participants 766 qualified doctors (425 men, 341 women) from all medical specialties (201 internal medicine, 76 general surgery, 67 anaesthetics, 54 radiology, 48 orthopaedics, 43 gynaecology, 36 neurology, 23 neurosurgery, 96 other specialties).

Data source Staff purchasing history from staff canteens’ electronic payment system linked to separate anonymised personal data from the human resource database.

Main outcome measure Numbers of coffees purchased per person per year.

Results 84% (644) of doctors purchased coffee at one of the hospital canteens. 70 772 coffees were consumed by doctors in 2014. There was a significant association between specialty and yearly coffee purchasing (F=12.45; P<0.01). On average orthopaedic surgeons purchased the most coffee per person per year (mean 189, SD 136) followed by radiologists (177, SD 191) and general surgeons (167, SD 138). Anaesthetists purchased the least coffee (39, SD 48). Male doctors bought significantly more coffees per person per year (128 (SD 140) v 86 (SD 86), t=−4.66, P<0.01) and twice as many espressos as female doctors (mean 27 (SD 46) v 10 (SD 19), t=−6.54, P<0.01). Hierarchical position was associated with coffee purchasing (F=4.55; P=0.04). Senior consultants (>5 years’ experience) bought most coffees per person per year (140, SD 169) and junior doctors and registrars bought fewest (95, SD 85). Propensity of buying rounds also increased with hierarchical position (χ2=556.24; P<0.01), with heads of departments buying more rounds than junior doctors (30% v 15%).

Conclusions Doctors commonly use coffee as a stimulant. Substantial variation exists between specialties. Surgeons drink notably more coffee than physicians, with orthopaedic surgeons consuming the greatest amount in the communal cafeteria setting, though this might reflect social tendencies rather than caffeine dependency. The hierarchical position is positively correlated with coffee consumption and generosity in buying rounds of coffee.

TASKS

Research question (including the population of interest): How much coffee do the doctors from all the specialties in Large Teaching Hospital Switzerland consume at work?

Sampling method: Convenience Sampling

Sample Description: 766 qualified doctors (425 men, 341 women) from all medical specialties (201 internal medicine, 76 general surgery, 67 anesthetics, 54 radiology, 48 orthopedics, 43 gynecology, 36 neurology, 23 neurosurgery, 96 other specialties) were sampled to evaluate doctors’ coffee consumption at work in Large teaching hospital, Switzerland.

Primary outcome: The primary outcome in this study is the “Number of coffees purchased per person per year.”

#import data set
nhanes<-read.csv(file = file.choose(), header = TRUE, na.strings = ".")
#summarize all of the variables in the data set at once
summary(nhanes)
##        ID          SurveyYr            Gender               Age       
##  Min.   :51624   Length:10000       Length:10000       Min.   : 0.00  
##  1st Qu.:56905   Class :character   Class :character   1st Qu.:17.00  
##  Median :62160   Mode  :character   Mode  :character   Median :36.00  
##  Mean   :61945                                         Mean   :36.74  
##  3rd Qu.:67039                                         3rd Qu.:54.00  
##  Max.   :71915                                         Max.   :80.00  
##                                                                       
##   AgeDecade           AgeMonths        Race1              Race3          
##  Length:10000       Min.   :  0.0   Length:10000       Length:10000      
##  Class :character   1st Qu.:199.0   Class :character   Class :character  
##  Mode  :character   Median :418.0   Mode  :character   Mode  :character  
##                     Mean   :420.1                                        
##                     3rd Qu.:624.0                                        
##                     Max.   :959.0                                        
##                     NA's   :5038                                         
##   Education         MaritalStatus        HHIncome          HHIncomeMid    
##  Length:10000       Length:10000       Length:10000       Min.   :  2500  
##  Class :character   Class :character   Class :character   1st Qu.: 30000  
##  Mode  :character   Mode  :character   Mode  :character   Median : 50000  
##                                                           Mean   : 57206  
##                                                           3rd Qu.: 87500  
##                                                           Max.   :100000  
##                                                           NA's   :811     
##     Poverty        HomeRooms        HomeOwn              Work          
##  Min.   :0.000   Min.   : 1.000   Length:10000       Length:10000      
##  1st Qu.:1.240   1st Qu.: 5.000   Class :character   Class :character  
##  Median :2.700   Median : 6.000   Mode  :character   Mode  :character  
##  Mean   :2.802   Mean   : 6.249                                        
##  3rd Qu.:4.710   3rd Qu.: 8.000                                        
##  Max.   :5.000   Max.   :13.000                                        
##  NA's   :726     NA's   :69                                            
##      Weight           Length          HeadCirc         Height     
##  Min.   :  2.80   Min.   : 47.10   Min.   :34.20   Min.   : 83.6  
##  1st Qu.: 56.10   1st Qu.: 75.70   1st Qu.:39.58   1st Qu.:156.8  
##  Median : 72.70   Median : 87.00   Median :41.45   Median :166.0  
##  Mean   : 70.98   Mean   : 85.02   Mean   :41.18   Mean   :161.9  
##  3rd Qu.: 88.90   3rd Qu.: 96.10   3rd Qu.:42.92   3rd Qu.:174.5  
##  Max.   :230.70   Max.   :112.20   Max.   :45.40   Max.   :200.4  
##  NA's   :78       NA's   :9457     NA's   :9912    NA's   :353    
##       BMI        BMICatUnder20yrs     BMI_WHO              Pulse       
##  Min.   :12.88   Length:10000       Length:10000       Min.   : 40.00  
##  1st Qu.:21.58   Class :character   Class :character   1st Qu.: 64.00  
##  Median :25.98   Mode  :character   Mode  :character   Median : 72.00  
##  Mean   :26.66                                         Mean   : 73.56  
##  3rd Qu.:30.89                                         3rd Qu.: 82.00  
##  Max.   :81.25                                         Max.   :136.00  
##  NA's   :366                                           NA's   :1437    
##     BPSysAve        BPDiaAve          BPSys1          BPDia1      
##  Min.   : 76.0   Min.   :  0.00   Min.   : 72.0   Min.   :  0.00  
##  1st Qu.:106.0   1st Qu.: 61.00   1st Qu.:106.0   1st Qu.: 62.00  
##  Median :116.0   Median : 69.00   Median :116.0   Median : 70.00  
##  Mean   :118.2   Mean   : 67.48   Mean   :119.1   Mean   : 68.28  
##  3rd Qu.:127.0   3rd Qu.: 76.00   3rd Qu.:128.0   3rd Qu.: 76.00  
##  Max.   :226.0   Max.   :116.00   Max.   :232.0   Max.   :118.00  
##  NA's   :1449    NA's   :1449     NA's   :1763    NA's   :1763    
##      BPSys2          BPDia2           BPSys3          BPDia3     
##  Min.   : 76.0   Min.   :  0.00   Min.   : 76.0   Min.   :  0.0  
##  1st Qu.:106.0   1st Qu.: 60.00   1st Qu.:106.0   1st Qu.: 60.0  
##  Median :116.0   Median : 68.00   Median :116.0   Median : 68.0  
##  Mean   :118.5   Mean   : 67.66   Mean   :117.9   Mean   : 67.3  
##  3rd Qu.:128.0   3rd Qu.: 76.00   3rd Qu.:126.0   3rd Qu.: 76.0  
##  Max.   :226.0   Max.   :118.00   Max.   :226.0   Max.   :116.0  
##  NA's   :1647    NA's   :1647     NA's   :1635    NA's   :1635   
##   Testosterone       DirectChol       TotChol         UrineVol1    
##  Min.   :   0.25   Min.   :0.390   Min.   : 1.530   Min.   :  0.0  
##  1st Qu.:  17.70   1st Qu.:1.090   1st Qu.: 4.110   1st Qu.: 50.0  
##  Median :  43.82   Median :1.290   Median : 4.780   Median : 94.0  
##  Mean   : 197.90   Mean   :1.365   Mean   : 4.879   Mean   :118.5  
##  3rd Qu.: 362.41   3rd Qu.:1.580   3rd Qu.: 5.530   3rd Qu.:164.0  
##  Max.   :1795.60   Max.   :4.030   Max.   :13.650   Max.   :510.0  
##  NA's   :5874      NA's   :1526    NA's   :1526     NA's   :987    
##    UrineFlow1        UrineVol2       UrineFlow2       Diabetes        
##  Min.   : 0.0000   Min.   :  0.0   Min.   : 0.000   Length:10000      
##  1st Qu.: 0.4030   1st Qu.: 52.0   1st Qu.: 0.475   Class :character  
##  Median : 0.6990   Median : 95.0   Median : 0.760   Mode  :character  
##  Mean   : 0.9793   Mean   :119.7   Mean   : 1.149                     
##  3rd Qu.: 1.2210   3rd Qu.:171.8   3rd Qu.: 1.513                     
##  Max.   :17.1670   Max.   :409.0   Max.   :13.692                     
##  NA's   :1603      NA's   :8522    NA's   :8524                       
##   DiabetesAge     HealthGen         DaysPhysHlthBad  DaysMentHlthBad 
##  Min.   : 1.00   Length:10000       Min.   : 0.000   Min.   : 0.000  
##  1st Qu.:40.00   Class :character   1st Qu.: 0.000   1st Qu.: 0.000  
##  Median :50.00   Mode  :character   Median : 0.000   Median : 0.000  
##  Mean   :48.42                      Mean   : 3.335   Mean   : 4.127  
##  3rd Qu.:58.00                      3rd Qu.: 3.000   3rd Qu.: 4.000  
##  Max.   :80.00                      Max.   :30.000   Max.   :30.000  
##  NA's   :9371                       NA's   :2468     NA's   :2466    
##  LittleInterest      Depressed          nPreg.ncies        nBabies      
##  Length:10000       Length:10000       Min.   : 1.000   Min.   : 0.000  
##  Class :character   Class :character   1st Qu.: 2.000   1st Qu.: 2.000  
##  Mode  :character   Mode  :character   Median : 3.000   Median : 2.000  
##                                        Mean   : 3.027   Mean   : 2.457  
##                                        3rd Qu.: 4.000   3rd Qu.: 3.000  
##                                        Max.   :32.000   Max.   :12.000  
##                                        NA's   :7396     NA's   :7584    
##    Age1stBaby    SleepHrsNight    SleepTrouble        PhysActive       
##  Min.   :14.00   Min.   : 2.000   Length:10000       Length:10000      
##  1st Qu.:19.00   1st Qu.: 6.000   Class :character   Class :character  
##  Median :22.00   Median : 7.000   Mode  :character   Mode  :character  
##  Mean   :22.65   Mean   : 6.928                                        
##  3rd Qu.:26.00   3rd Qu.: 8.000                                        
##  Max.   :39.00   Max.   :12.000                                        
##  NA's   :8116    NA's   :2245                                          
##  PhysActiveDays    TVHrsDay          CompHrsDay        TVHrsDayChild  
##  Min.   :1.000   Length:10000       Length:10000       Min.   :0.000  
##  1st Qu.:2.000   Class :character   Class :character   1st Qu.:1.000  
##  Median :3.000   Mode  :character   Mode  :character   Median :2.000  
##  Mean   :3.744                                         Mean   :1.939  
##  3rd Qu.:5.000                                         3rd Qu.:3.000  
##  Max.   :7.000                                         Max.   :6.000  
##  NA's   :5337                                          NA's   :9347   
##  CompHrsDayChild Alcohol12PlusYr      AlcoholDay      AlcoholYear   
##  Min.   :0.000   Length:10000       Min.   : 1.000   Min.   :  0.0  
##  1st Qu.:0.000   Class :character   1st Qu.: 1.000   1st Qu.:  3.0  
##  Median :1.000   Mode  :character   Median : 2.000   Median : 24.0  
##  Mean   :2.198                      Mean   : 2.914   Mean   : 75.1  
##  3rd Qu.:6.000                      3rd Qu.: 3.000   3rd Qu.:104.0  
##  Max.   :6.000                      Max.   :82.000   Max.   :364.0  
##  NA's   :9347                       NA's   :5086     NA's   :4078   
##    SmokeNow           Smoke100          Smoke100n            SmokeAge    
##  Length:10000       Length:10000       Length:10000       Min.   : 6.00  
##  Class :character   Class :character   Class :character   1st Qu.:15.00  
##  Mode  :character   Mode  :character   Mode  :character   Median :17.00  
##                                                           Mean   :17.83  
##                                                           3rd Qu.:19.00  
##                                                           Max.   :72.00  
##                                                           NA's   :6920   
##    Marijua.         AgeFirstMarij   RegularMarij        AgeRegMarij   
##  Length:10000       Min.   : 1.00   Length:10000       Min.   : 5.00  
##  Class :character   1st Qu.:15.00   Class :character   1st Qu.:15.00  
##  Mode  :character   Median :16.00   Mode  :character   Median :17.00  
##                     Mean   :17.02                      Mean   :17.69  
##                     3rd Qu.:19.00                      3rd Qu.:19.00  
##                     Max.   :48.00                      Max.   :52.00  
##                     NA's   :7109                       NA's   :8634   
##   HardDrugs           SexEver              SexAge      SexNumPartnLife  
##  Length:10000       Length:10000       Min.   : 9.00   Min.   :   0.00  
##  Class :character   Class :character   1st Qu.:15.00   1st Qu.:   2.00  
##  Mode  :character   Mode  :character   Median :17.00   Median :   5.00  
##                                        Mean   :17.43   Mean   :  15.09  
##                                        3rd Qu.:19.00   3rd Qu.:  12.00  
##                                        Max.   :50.00   Max.   :2000.00  
##                                        NA's   :4460    NA's   :4275     
##  SexNumPartYear     SameSex          SexOrientation      Preg.ntNow       
##  Min.   : 0.000   Length:10000       Length:10000       Length:10000      
##  1st Qu.: 1.000   Class :character   Class :character   Class :character  
##  Median : 1.000   Mode  :character   Mode  :character   Mode  :character  
##  Mean   : 1.342                                                           
##  3rd Qu.: 1.000                                                           
##  Max.   :69.000                                                           
##  NA's   :5072
#calculate summary statistics for SleepHrsNight variable
summary(nhanes$SleepHrsNight)
##    Min. 1st Qu.  Median    Mean 3rd Qu.    Max.    NA's 
##   2.000   6.000   7.000   6.928   8.000  12.000    2245
#find range of 'SleepHrsNight'
SHS_range <- range(nhanes$SleepHrsNight, na.rm = TRUE)
cat("Range:", SHS_range[1], "to", SHS_range[2], "\n")
## Range: 2 to 12
# Find the standard deviation of 'SleepHrsNight'
SHS_sd <- sd(nhanes$SleepHrsNight, na.rm = TRUE)
cat("Standard Deviation:", SHS_sd, "\n")
## Standard Deviation: 1.346729
str(nhanes)
## 'data.frame':    10000 obs. of  76 variables:
##  $ ID              : int  51624 51624 51624 51625 51630 51638 51646 51647 51647 51647 ...
##  $ SurveyYr        : chr  "2009_10" "2009_10" "2009_10" "2009_10" ...
##  $ Gender          : chr  "male" "male" "male" "male" ...
##  $ Age             : int  34 34 34 4 49 9 8 45 45 45 ...
##  $ AgeDecade       : chr  " 30-39" " 30-39" " 30-39" " 0-9" ...
##  $ AgeMonths       : int  409 409 409 49 596 115 101 541 541 541 ...
##  $ Race1           : chr  "White" "White" "White" "Other" ...
##  $ Race3           : chr  NA NA NA NA ...
##  $ Education       : chr  "High School" "High School" "High School" NA ...
##  $ MaritalStatus   : chr  "Married" "Married" "Married" NA ...
##  $ HHIncome        : chr  "25000-34999" "25000-34999" "25000-34999" "20000-24999" ...
##  $ HHIncomeMid     : int  30000 30000 30000 22500 40000 87500 60000 87500 87500 87500 ...
##  $ Poverty         : num  1.36 1.36 1.36 1.07 1.91 1.84 2.33 5 5 5 ...
##  $ HomeRooms       : int  6 6 6 9 5 6 7 6 6 6 ...
##  $ HomeOwn         : chr  "Own" "Own" "Own" "Own" ...
##  $ Work            : chr  "NotWorking" "NotWorking" "NotWorking" NA ...
##  $ Weight          : num  87.4 87.4 87.4 17 86.7 29.8 35.2 75.7 75.7 75.7 ...
##  $ Length          : num  NA NA NA NA NA NA NA NA NA NA ...
##  $ HeadCirc        : num  NA NA NA NA NA NA NA NA NA NA ...
##  $ Height          : num  165 165 165 105 168 ...
##  $ BMI             : num  32.2 32.2 32.2 15.3 30.6 ...
##  $ BMICatUnder20yrs: chr  NA NA NA NA ...
##  $ BMI_WHO         : chr  "30.0_plus" "30.0_plus" "30.0_plus" "12.0_18.5" ...
##  $ Pulse           : int  70 70 70 NA 86 82 72 62 62 62 ...
##  $ BPSysAve        : int  113 113 113 NA 112 86 107 118 118 118 ...
##  $ BPDiaAve        : int  85 85 85 NA 75 47 37 64 64 64 ...
##  $ BPSys1          : int  114 114 114 NA 118 84 114 106 106 106 ...
##  $ BPDia1          : int  88 88 88 NA 82 50 46 62 62 62 ...
##  $ BPSys2          : int  114 114 114 NA 108 84 108 118 118 118 ...
##  $ BPDia2          : int  88 88 88 NA 74 50 36 68 68 68 ...
##  $ BPSys3          : int  112 112 112 NA 116 88 106 118 118 118 ...
##  $ BPDia3          : int  82 82 82 NA 76 44 38 60 60 60 ...
##  $ Testosterone    : num  NA NA NA NA NA NA NA NA NA NA ...
##  $ DirectChol      : num  1.29 1.29 1.29 NA 1.16 1.34 1.55 2.12 2.12 2.12 ...
##  $ TotChol         : num  3.49 3.49 3.49 NA 6.7 4.86 4.09 5.82 5.82 5.82 ...
##  $ UrineVol1       : int  352 352 352 NA 77 123 238 106 106 106 ...
##  $ UrineFlow1      : num  NA NA NA NA 0.094 ...
##  $ UrineVol2       : int  NA NA NA NA NA NA NA NA NA NA ...
##  $ UrineFlow2      : num  NA NA NA NA NA NA NA NA NA NA ...
##  $ Diabetes        : chr  "No" "No" "No" "No" ...
##  $ DiabetesAge     : int  NA NA NA NA NA NA NA NA NA NA ...
##  $ HealthGen       : chr  "Good" "Good" "Good" NA ...
##  $ DaysPhysHlthBad : int  0 0 0 NA 0 NA NA 0 0 0 ...
##  $ DaysMentHlthBad : int  15 15 15 NA 10 NA NA 3 3 3 ...
##  $ LittleInterest  : chr  "Most" "Most" "Most" NA ...
##  $ Depressed       : chr  "Several" "Several" "Several" NA ...
##  $ nPreg.ncies     : int  NA NA NA NA 2 NA NA 1 1 1 ...
##  $ nBabies         : int  NA NA NA NA 2 NA NA NA NA NA ...
##  $ Age1stBaby      : int  NA NA NA NA 27 NA NA NA NA NA ...
##  $ SleepHrsNight   : int  4 4 4 NA 8 NA NA 8 8 8 ...
##  $ SleepTrouble    : chr  "Yes" "Yes" "Yes" NA ...
##  $ PhysActive      : chr  "No" "No" "No" NA ...
##  $ PhysActiveDays  : int  NA NA NA NA NA NA NA 5 5 5 ...
##  $ TVHrsDay        : chr  NA NA NA NA ...
##  $ CompHrsDay      : chr  NA NA NA NA ...
##  $ TVHrsDayChild   : int  NA NA NA 4 NA 5 1 NA NA NA ...
##  $ CompHrsDayChild : int  NA NA NA 1 NA 0 6 NA NA NA ...
##  $ Alcohol12PlusYr : chr  "Yes" "Yes" "Yes" NA ...
##  $ AlcoholDay      : int  NA NA NA NA 2 NA NA 3 3 3 ...
##  $ AlcoholYear     : int  0 0 0 NA 20 NA NA 52 52 52 ...
##  $ SmokeNow        : chr  "No" "No" "No" NA ...
##  $ Smoke100        : chr  "Yes" "Yes" "Yes" NA ...
##  $ Smoke100n       : chr  "Smoker" "Smoker" "Smoker" NA ...
##  $ SmokeAge        : int  18 18 18 NA 38 NA NA NA NA NA ...
##  $ Marijua.        : chr  "Yes" "Yes" "Yes" NA ...
##  $ AgeFirstMarij   : int  17 17 17 NA 18 NA NA 13 13 13 ...
##  $ RegularMarij    : chr  "No" "No" "No" NA ...
##  $ AgeRegMarij     : int  NA NA NA NA NA NA NA NA NA NA ...
##  $ HardDrugs       : chr  "Yes" "Yes" "Yes" NA ...
##  $ SexEver         : chr  "Yes" "Yes" "Yes" NA ...
##  $ SexAge          : int  16 16 16 NA 12 NA NA 13 13 13 ...
##  $ SexNumPartnLife : int  8 8 8 NA 10 NA NA 20 20 20 ...
##  $ SexNumPartYear  : int  1 1 1 NA 1 NA NA 0 0 0 ...
##  $ SameSex         : chr  "No" "No" "No" NA ...
##  $ SexOrientation  : chr  "Heterosexual" "Heterosexual" "Heterosexual" NA ...
##  $ Preg.ntNow      : chr  NA NA NA NA ...
# create a histogram for the SleepHrsNight variable
hist(nhanes$SleepHrsNight, main="Histogram of Sleep Hours Night", xlab="SleepHrsNight", breaks = 10)


Describe the shape, center, and spread for the SleepHrsNight variable.
Shape: Symmetric (Normal Distribution) Measures of Centre: Mean = 6.928, Median = 7 Measures of spread:Standard deviation = 1.35, IQR = 2

Does the number of hours of sleep for weekday or workdays appear to be approximately normally distributed? Explain your reasoning
The mean (6.928) and the median (7) are approximately the same.

# what is the probability a participant from the population of adults and children in the US gets less than 5 hours of sleep on the weekday or workday (i.e., SleepHrsNight < 5)?
pnorm(5, mean = 6.928, sd = 1.35)
## [1] 0.07662461
# what is the probability a participant from the population of adults and children in the US gets between 5 and 8 hours of sleep on the weekday or workday (i.e., 5 < SleepHrsNight < 8)
pnorm(8, mean = 6.928, sd = 1.35) - pnorm(5, mean = 6.928, sd = 1.35)
## [1] 0.7097992
# what is the probability a participant from the population of adults and children in the US gets more than 8 hours of sleep on the weekday or workday (i.e., SleepHrsNight > 8)
1 - pnorm(8, mean = 6.928, sd = 1.35)
## [1] 0.2135762
21. Using your software of choice, calculate summary statistics for the HealthGen variable. Share your code and output.
First, convert the “HealthGen” variable which is currently treated as a character variable to a factor or categorical variable. You can convert it to a factor using the factor() function in R. Then summary function

# Convert 'HealthGen' to a factor
nhanes$HealthGen <- factor(nhanes$HealthGen)

# Calculate summary statistics for 'HealthGen'
summary(nhanes$HealthGen)
## Excellent      Fair      Good      Poor     Vgood      NA's 
##       878      1010      2956       187      2508      2461
# Create a table of counts for each level of 'HealthGen'
healthgen_counts <- table(nhanes$HealthGen)

# Calculate proportions
prop_table <- prop.table(healthgen_counts)
# what is the probability that 1 participant from the population adults and children in the US has poor health?
dbinom(1, size = 100, prob = 0.025)
## [1] 0.2038905
#what is the probability that more than 5 participants from the population adults and children in the US have poor health?
1 - pbinom(6, size = 100, prob = 0.025)
## [1] 0.01297761
# what is the probability that at least 2 participants from the population adults and children in the US have poor health?
1 - pbinom(2, size = 100, prob = 0.025)
## [1] 0.4578081
