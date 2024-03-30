#  𝐐𝐮𝐨𝐫𝐚 𝐐𝐮𝐞𝐬𝐭𝐢𝐨𝐧 𝐏𝐚𝐢𝐫
###  𝐁𝐮𝐬𝐢𝐧𝐞𝐬𝐬 𝐏𝐫𝐨𝐛𝐥𝐞𝐦 𝐈𝐝𝐞𝐧𝐭𝐢𝐟𝐢𝐜𝐚𝐭𝐢𝐨𝐧:

### 𝐓𝐚𝐬𝐤: 𝐏𝐫𝐞𝐝𝐢𝐜𝐭 𝐢𝐟 𝐩𝐚𝐢𝐫𝐬 𝐨𝐟 𝐪𝐮𝐞𝐬𝐭𝐢𝐨𝐧𝐬 𝐡𝐚𝐯𝐞 𝐭𝐡𝐞 𝐬𝐚𝐦𝐞 𝐦𝐞𝐚𝐧𝐢𝐧𝐠.
#### 𝐒𝐨𝐮𝐫𝐜𝐞: Quora question dataset.
### 𝐃𝐚𝐭𝐚 𝐎𝐯𝐞𝐫𝐯𝐢𝐞𝐰:
**Data Source**: Train.csv file.

**Features**: qid1, qid2, question1, question2, is_duplicate.

**Size**: 60MB, 404,290 rows.
### 𝐈𝐦𝐩𝐨𝐫𝐭 𝐍𝐞𝐜𝐞𝐬𝐬𝐚𝐫𝐲 𝐋𝐢𝐛𝐫𝐚𝐫𝐢𝐞𝐬:

TensorFlow, Keras, NLTK, Reg-ex, NumPy, Pandas, Matplotlib, Seaborn, etc.
### 𝐋𝐨𝐚𝐝 𝐃𝐚𝐭𝐚 & 𝐁𝐚𝐬𝐢𝐜 𝐂𝐡𝐞𝐜𝐤𝐬:

* Load and inspect training and testing data.

* Check data's head, tail, shape, and information.

* Examine unique questions in the dataset.
### 𝐄𝐱𝐩𝐥𝐨𝐫𝐚𝐭𝐨𝐫𝐲 𝐃𝐚𝐭𝐚 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 (𝐄𝐃𝐀):

* Assess data balance.

* Utilize automated EDA tools for insights.

### 𝐑𝐞𝐩𝐞𝐚𝐭𝐞𝐝 𝐐𝐮𝐞𝐬𝐭𝐢𝐨𝐧𝐬 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬:
* Count unique and repeated questions.

* Visualize repeated questions distribution.

### 𝐒𝐩𝐥𝐢𝐭 𝐃𝐚𝐭𝐚 𝐢𝐧𝐭𝐨 𝐓𝐫𝐚𝐢𝐧𝐢𝐧𝐠 𝐚𝐧𝐝 𝐓𝐞𝐬𝐭𝐢𝐧𝐠 𝐒𝐞𝐭𝐬:

Define X_train & y_train arrays.

Create X_test & y_test arrays.

### 𝐃𝐚𝐭𝐚 𝐏𝐫𝐞-𝐩𝐫𝐨𝐜𝐞𝐬𝐬𝐢𝐧𝐠:

* Check for missing values and duplicates.

* Perform text pre-processing using Keras.

* Pad and sequence the text.

* Load GloVe word embeddings for semantic representation.

### 𝐋𝐒𝐓𝐌 𝐌𝐨𝐝𝐞𝐥 𝐈𝐦𝐩𝐥𝐞𝐦𝐞𝐧𝐭𝐚𝐭𝐢𝐨𝐧:

* Utilize Long Short-Term Memory (LSTM) for deep learning.

* Create separate models for each question.

* Merge the model outputs.

### 𝐕𝐢𝐬𝐮𝐚𝐥𝐢𝐳𝐞 𝐌𝐨𝐝𝐞𝐥 𝐀𝐫𝐜𝐡𝐢𝐭𝐞𝐜𝐭𝐮𝐫𝐞:

* Generate a visual representation of the model.
 
###  𝐂𝐨𝐦𝐩𝐢𝐥𝐞 𝐚𝐧𝐝 𝐓𝐫𝐚𝐢𝐧 𝐌𝐨𝐝𝐞𝐥:

* Use Adam optimizer with sparse categorical cross-entropy loss.
 
* Train the model with specified batch size and epochs.
  ### 𝐏𝐥𝐨𝐭 𝐓𝐫𝐚𝐢𝐧𝐢𝐧𝐠 𝐋𝐨𝐬𝐬 𝐚𝐧𝐝 𝐀𝐜𝐜𝐮𝐫𝐚𝐜𝐲:

* Visualize training progress using loss and accuracy plots.

* Prediction Using Test Data:

* Generate predictions using pre-processed test data.

### 𝐌𝐨𝐝𝐞𝐥 𝐒𝐚𝐯𝐢𝐧𝐠:

* Save the trained model using .h5 extension.
### 𝐂𝐡𝐚𝐥𝐥𝐞𝐧𝐠𝐞𝐬 𝐅𝐚𝐜𝐞𝐝:

* Understanding the business problem.

* Choosing appropriate text processing techniques.
 * Dealing with lengthy training times.
**This outline covers the entire process from data loading to model evaluation, encapsulating key steps and challenges encountered in the project**.
