# Breast Cancer Detection from thermograms.
Breast cancer, the most common invasive cancer, causes deaths of thousands of women in the world every year. Early detection of the same is a remedy to lessen the death rate. Hence, screening of breast cancer in its early stage is utmost required. However, in the developing nations not many can afford the screening and detection procedures owing to its cost. Hence, an effective and less expensive way of detecting breast cancer is performed using thermography which, unlike other methods, can be used on women of various ages. To this end, we propose a computer aided breast cancer detection system that accepts thermal breast images to detect the same. Here, we use the pre-trained DenseNet121 model as a feature extractor to build a classifier for the said purpose. Before extracting features, we work on the original thermal breast images to get outputs using two edge detectors - Prewitt and Roberts. These two edge-maps along with the original image make the input to the DenseNet121 model as a 3-channel image. The thermal breast image dataset namely, Database for Mastology Research (DMR-IR) is used to evaluate performance of our model. We achieve the highest classification accuracy of 98.80\% on the said database, which outperforms many state-of-the-art methods, thereby confirming the superiority of the proposed model.
