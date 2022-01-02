# Datacontest_07_2021(team project)
## Data analysis contest in South Korea on July, 2021(won a third prize)
![july_contest](https://user-images.githubusercontent.com/86550939/147870207-51dc7836-13fb-4b7d-a86a-29c8d2ef3c6e.jpg)
##  The number of eco-friendly cars and the current status of air pollution by region

## Contents
1. Among the various types of air pollution, the correlation between CO, that is, carbon monoxide pollution, and electric vehicles among various types of eco-friendly cars was investigated
2. Subsidies for electric vehicles are provided differently in each region. Depending on the results of the survey, this project would like to suggest where subsidies should be paid more actively.
3. The datasets from Seoul, Gyeonggi, Incheon, Daegu and Jeju were collected and conducted.
4. The expected effect of the project provides prediction data that carbon monoxide pollution will decrease as the proportion of electric vehicles increases, raising the need for electric vehicles, further informing citizens of one of the measures for global warming, and increasing the size of subsidies.

## Analysis
1. Used Jupyter notebook for visualising the dataset we have
2. Tried using linear-regression and non-linear regression but the forecast data of CO pollution in the far future showed minus value, so failed to use them
3. Since a logarithmic function is a function that converges to zero, we used logistic regression for getting the forecast data of CO pollution according to the increase of the proportion of electric cars.

> What should have been modified
> > By working on a new project on October, I found that it would be much nicer if we used the characteristic of time series data. If we did so, we could use LSTM or prophet for getting the forecast data of CO pollustion way more precise. 


#### Data source
#### 1. https://sgis.kostat.go.kr/view/thematicMap/thematicMapMain?stat_thema_map_id=EItIIxKpqw20160121115806992KLww5xGJKJ&theme=CTGR_005&mapType=03&CTGRS=CTGR_001:recommend,CTGR_002:recommend,CTGR_003:recommend,CTGR_004:recommend,CTGR_005:recommend
#### 2. https://www.airkorea.or.kr/web/detailViewDown?pMENU_NO=125
#### 3. https://www.ev.or.kr/portal/localInfo

##### Dataset and code consist in Korean.
