# reverse-image
Reverse Image Search for Satellite Imagery on UC Merced Land Use Dataset
1. We extract features from pretrained models like VGG-16, VGG-19, ResNet-50, InceptionV3 and MobileNet and benchmark them using the UC Merced Land Use Dataset.
2. We write an indexer to index features and search for most similar features using various nearest neighbor algorithms, and explore various methods of visualizing plots.
3. We benchmark the algorithms based on the time it takes to index images and locate the most similar image based on its features using the UC Merced Land Use Dataset. We also experiment with t-SNE and PCA.
4. We experiment with different visualization techniques on the results, t-SNE and PCA on the results and calculate the accuracies of the features obtained from the pretrained and finetuned models.
5. We experiment with PCA and figure out what is the optimum length of the features to use in our experiments and then we find the least accurate (worst) performing categories, visualize them with t-SNE, fine-tune and then see how their t-SNE graph changes.
