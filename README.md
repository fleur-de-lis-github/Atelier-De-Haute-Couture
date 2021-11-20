# Atelier-De-Haute-Couture

## Problem Scenario
## Business Client
![ChessUrl](https://images.squarespace-cdn.com/content/v1/5d48ece5c9b54700015ba784/1603698100793-GRLKR2D44TY660KTLMNB/Milan+Fashion+App+UI+Kit-web-15.gif"chess")


## Project Workflow
- Import Libraries
- Extract Dataset
- Feature Labelling
- Data Visualization
- Distribution of Labels
- Split the Data
- Reshaping the Images
- Normalization
- Build and Train the Model
- Evaluate and Visualize the Predictions

## Data Summary
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. Zalando intends Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits. The original MNIST dataset contains a lot of handwritten digits. Members of the AI/ML/Data Science community love this dataset and use it as a benchmark to validate their algorithms. In fact, MNIST is often the first dataset researchers try.  "If it doesn't work on MNIST, it won't work at all", they said. "Well, if it does work on MNIST, it may still fail on others."

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total.
Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255.
The training and test data sets have 785 columns.
The first column consists of the class labels (see above), and represents the article of clothing.
The rest of the columns contain the pixel-values of the associated image.
To locate a pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27. The pixel is located on row i and column j of a 28 x 28 matrix. For example, pixel31 indicates the pixel that is in the fourth column from the left, and the second row from the top, as in the ascii-diagram below.

## Citation
