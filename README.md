# Atelier-De-Haute-Couture

## Problem Scenario

Covid-19 has fast forwarded fashion into a digital future that it had been reluctant to embrace. As shops and factories closed and catwalk shows and fashion weeks were cancelled, sales at bricks and mortar stores have slumped by double digits in every major market, with devastating impact. Many of the brands and retailers that once filled the high streets and malls are dying. `Barneys New York, Neiman Marcus, Lord & Taylor, John Varvatos, Brooks Bros, Diane von Furstenberg, TopShop, J Crew, Oasis, Debenhams and True Religion`, to name just a few, have either tipped into bankruptcy or teeter on the brink.

Brands have had no choice but ramp up their digital offerings fast.

`Reason that drove traditional luxury brands to stay away from eCommerce has been the perceived lack of control quality of the sales environment and pricing, on third party multibrand online pureplay platforms in particular. In order to maintain their high profile clientelle, these fashion websites must have low margin error when it comes to clothes fit and apparel categorization.`

## Our Approach
```diff
 One of the most challenging multi-classes classification problems is fashion classification 
in which labels that characterize the clothes type are assigned to the images.

@@ The difficulty of this multi-classes fashion classification problem is due to the richness of the clothes @@
@@ properties and the high depth of clothes categorization as well. This complicated depth makes different labels/classes to have similar features. @@

This project tries to enhance the performance of the fashion classification problem on the Fashion-MNIST Dataset 
, which contains 70,000 images (each image is labeled from the 10 categories shown in Figure 1: T-shirt/top, Trousers,
Pullover, Dress, Coat, Sandals, Shirt, Sneaker, Bag and Ankle boot).

@@ CNN can learn complex, high-dimensional, non-linear mappings from a very large number of data (images). Moreover,  @@
@@ CNN gives an excellent classification average for images . The main advantages of CNN are that it extracts the salient  @@
@@ features that are never changed, and it is invariant to shifting, scaling and distortions of input data (images).  @@
 
```

## Business Client
![ChessUrl](https://images.squarespace-cdn.com/content/v1/5d48ece5c9b54700015ba784/1603698100793-GRLKR2D44TY660KTLMNB/Milan+Fashion+App+UI+Kit-web-15.gif"chess")

```diff
- Jonathan Siboni, of Paris-based data intelligence firm Luxurynsight, estimates the overall share of global online fashion sales has doubled to 22 per cent since March. And - -- that’s just beginning. With Chinese consumers, who are forecast to account for nearly half of all luxury goods purchases by 2025, turning increasingly to the likes of Alibaba - or brands’ own website because they cannot travel overseas to buy as they used to, the global figure is likely to hit 25 per cent by 2022.

- The Kering conglomerate, which includes Gucci, Saint Laurent and Bottega Veneta, has seen its e-commerce revenue more than double year-on-year. The market value of Farfetch -  - has >risen more than four fold since the start of the year to reach $18.6bn.
```

## Project Workflow
:pushpin:- Import Libraries <br>
:pushpin:- Extract Dataset <br>
:pushpin:- Feature Labelling <br>
:pushpin:- Data Visualization <br>
:pushpin:- Distribution of Labels <br>
:pushpin:- Split the Data <br>
:pushpin:- Reshaping the Images <br>
:pushpin:- Normalization <br>
:pushpin:- Build and Train the Model <br>
:pushpin:- Evaluate and Visualize the Predictions

## Data Summary
:closed_book:Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. 

:blue_book:Zalando intends Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits. The original MNIST dataset contains a lot of handwritten digits. Members of the AI/ML/Data Science community love this dataset and use it as a benchmark to validate their algorithms. In fact, MNIST is often the first dataset researchers try.  "If it doesn't work on MNIST, it won't work at all", they said. "Well, if it does work on MNIST, it may still fail on others."

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total.

:orange_book:Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns.The first column consists of the class labels (see above), and represents the article of clothing.
The rest of the columns contain the pixel-values of the associated image.

:ledger:To locate a pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27. The pixel is located on row i and column j of a 28 x 28 matrix. For example, pixel31 indicates the pixel that is in the fourth column from the left, and the second row from the top, as in the ascii-diagram below.

## Citation
- https://beei.org/index.php/EEI/article/view/2750
- https://link.springer.com/chapter/10.1007/978-3-030-20912-4_17
- https://openaccess.thecvf.com/content_ICCVW_2019/html/CVFAD/Cho_Leveraging_Class_Hierarchy_in_Fashion_Classification_ICCVW_2019_paper.html
