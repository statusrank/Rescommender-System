# Rescommender-System
Experiment and Dataset about the RS<br>
[User Behavior Data on Taobao App](https://tianchi.aliyun.com/datalab/dataSet.html?spm=5176.100073.0.0.16ca3ea7n771BU&dataId=46)<br>
[The Dataset Format](https://tianchi.aliyun.com/competition/information.htm?spm=5176.100067.5678.2.2f7378f6K40P0t&raceId=1)<br>
[User Behavior Data from Taobao for Recommendation](https://tianchi.aliyun.com/datalab/dataSet.html?spm=5176.100073.0.0.740b3ea7jTKRA1&dataId=649)
## SPTF：SPTF: A Scalable Probabilistic Tensor Factorization Model for Semantic-Aware Behavior Prediction
[论文](https://ieeexplore.ieee.org/document/8215531)
[Blog](https://statusrank.xyz/2018/11/14/SPTF/)<br>
### Dataset
  It is publiced by the Paper authors.Thanks!<br>
  [The dataset is provided by T-mall in 2014.]( http://pan.baidu.com/s/1mhQ0ifQ)  password: jrlb <br>
  This dataset contains 480,723 products,10000 users and their generated twenty-million behavior records during 18/11/2014-18/12/2014.
  #### Dataset Format
   user_id item_id action type  // user_id 标识唯一user,item_id 标识唯一item, action type  = {1,2,3,4} 分别表示click、add-to-favorite、add-to-cart、purchase  
   We also have three sets,including a set of user,item and action type.<br>
   In this experiment , we randomly generate them as a Gaussian prior.<br>
### Experiment
  Based on the paper mentioned, the Dataset should have an column of timestamps.But I can't find this.It only includes three columns that I mentioned above.
  Firstly ,they rank these behavior records according to their timestamps,and the train/test/validation is 80/10/10 percent.
  The details of the experiment see Blog,mentioned above.

## Extreme Learning to Rank via Low Rank Assumption
### Dataset
  [Yahoo! Movies User Ratings and DescriptiveContent Information ](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r)<br>
  [ MovieLens 20M Dataset](https://grouplens.org/datasets/movielens/)<br>
  It contains 20000263 ratings and 465564 tag applications across 27278 movies. These data were created by 138493 users.
  #### Dataset Format 
  Movies.csv<br>
    movieId,title,genres<br>
  tags.csv<br>
    userId,movieId,tag,timestamp<br>
  ratings.csv
    userId,movieId,rating,timestamp
  link.csv
    movieId,imdbId,tmdbId

