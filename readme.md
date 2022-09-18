# Customer Segmentation using Machine Learning

## Objectives<br>
• Improve customer satisfaction<br>
• Reduce wastage of unwanted products<br>
• Improve marketing strategy<br>
• Targeting audience on the basis of their needs.<br>

## Customer Segmentation using Unsupervised Machine Learning(K-means clustering algorithm)<br>
  * Customer behavioural traits like number of products ordered, average return rate and total spending were taken
  into account, scaled data by logarithmic scaling.
  * Predicted relevant customer segmentation groups using k-means clustering algorithm

## Methodology:
We will be following the following steps for achieving
our goal,
1. Segmentation Basis
2. Data Preparation
3. Segmentation with K-means Clustering
4. Hyper-parameter Tuning
5. Visualization and Interpretation of the Results
<br>

### Dataset Features:<br>
![img1](/images/1.png)<br>
### Considered attributes:<br>
![img1](/images/2.png)<br>
![img1](/images/3.png)<br>
### Feature visuzlization:<br>
![img1](/images/4.png)<br>
### Distribution of Features after log Transformation
![img1](/images/5.png)<br>
![img1](/images/6.png)<br>
### Clustered Sum vs K:<br>
![img1](/images/7.png)<br>
### Assigned clusters:<br>
![img1](/images/8.png)<br>
![img1](/images/9.png)<br>
### Customer groups at k=4:<br>
![img1](/images/10.png)<br>
### Comparing results with different algorithms used:<br>
![img1](/images/12.png)<br>
### Colab notebook K-means code:<br>
![img1](/images/21.png)<br>

## Results:<br>
On taking a further look at the cluster magnitudes,
1. Blue group comprises of 42% of total customers, marking a huge share. Any further improvements made in this category would indeed contribute to the high increase in revenue.
2. Red and purple group together comprise of 50% of total customers.
3. Green group consists of 8% of the total customers, they order multiple products and they are highly likely to keep them.To maintain and possibly expand this group, special deals and pre-product launches might help. Moreover, they can be magnets for new customers impacting the expansion of the customer base.

## Concluding Remarks:<br>
The customer segmentation model was approached from a behavioural point of view, and the primary features taken into account to achieve this effect were number of products ordered, average return rate and total spending for each customer.<br>
The dataset initially was random. It could not differentiate into potential customer sweet spots or categorize them into any certain groups. On applying the k-means clustering the dataset could be categorized into various groups and accordingly the outcomes of target specific audience could be achieved.
<br>
## new
can render the jupyter notebook in a react-app
