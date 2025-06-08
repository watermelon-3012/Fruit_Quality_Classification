# ML2-Group2-Fruit_Quality_Classification

Group Members:
1. Hoang Kim Huong - huonghk.22ba13158@usth.edu.vn
2. Nguyen Thi Ngoc Lan - lanntn.22ba13186@usth.edu.vn
3. Doan Ngoc Linh - linhdn.22ba13190@usth.edu.vn
4. Le Sy Han - hanls.23bi14150@usth.edu.vn
5. Le Hoang Dat - datlh.23bi14087@usth.edu.vn

This project examines the application of convolutional neural networks (CNNs) in the classification of fruit images to distinguish between three types of fruits (apples, bananas, and oranges) and fresh or rotten samples. Ensuring fruit quality is crucial in the food industry to prevent health risks and reduce waste. A dataset of 1800 images was collected, consisting of equal numbers of 6 classes: 'Fresh_Apple', 'Fresh_Banana', 'Fresh_Orange', 'Rotten_Apple', 'Rotten_Banana', 'Rotten_Orange' and preprocessed using resizing, normalization techniques. A CNN model was developed using TensorFlow and trained with a categorical cross-entropy loss function and the Adam optimizer. The model achieved an accuracy of 95.37\% on the validation set and 91\% on the test set, indicating a strong ability to generalize. Performance was further analyzed using a confusion matrix and precision-recall metrics. These results suggest that deep learning, specifically CNNs, can be effectively utilized for automated food quality control. Future work may involve expanding the dataset, testing on real-time systems, and integrating the model into supply chain monitoring solutions.
