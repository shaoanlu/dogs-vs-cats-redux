# dogs-vs-cats-redux

https://shaoanlu.wordpress.com/2017/04/22/deep-learning-on-floyd-dogs-vs-cats-redux-kaggle-competition/

Kaggle dogs vs cats redux on flyodhub

**res50_bneck_fconv.ipynb** and **res50_fc_and_incep.ipynb:** ResNet50 as base moedl with different output layers. Result: scored in the top 8% on public LB (with model ensembling in **avg_subm.ipynb**).



**res50_incepV3_Xcept.ipynb:** ResNet50, inceptionV3 adn Xception as base models with simple fully-connected output layers. Result: scored within top 2% on public LB



**knn_image.ipynb:** Averaging test image predictinos using k-Nearest-neighbors.



**opt_experiment.ipynb**: Comparison between optimizers: SGD, Adam Nadam and RMSprop. Result shows that SGD with momentum has better performnace on validation data than adaptive optimizers. [See this blog post for detail.](https://shaoanlu.wordpress.com/2017/05/29/sgd-all-which-one-is-the-best-optimizer-dogs-vs-cats-toy-experiment/)
