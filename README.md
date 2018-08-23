# tfjs-mnist-workshop

This is an e2e TensorFlow workshop from model training using Keras API all the way to visualization using TensorFlow.js

User will need to complete exercises (.ipynb files) under py/ folder. Reference implementation could be found from /py/solutions folder.

# User guide

* Prepare environment
  * For Windows users, download and install ANaconda with either Python 2 or Python 3
  * For Linux/Mac users, you should already have Python installed
* Install dependencies
  * `pip install -r requirements.txt`
  * If you're facing connectivity issues, please use `pip install -i https://pypi.tuna.tsinghua.edu.cn/simple -r requirements.txt`
* Visualize the initial model in browser
  * For Python 2 users, `python -m SimpleHTTPServer`
  * For Python 3 users, `python -m http.server`
  * Open localhost:8080 in your browser
  * Most of the predictions are wrong (red) because the model is doing random guess
* Coding
  * Use jupyter notebook to complete an exercise and generate a model
* Convert the mdoel to TF JS format
  * For windows users, `convert.bat PATH_TO_THE_H5_FILE`
  * For Linux/Mac users, `convert.sh PATH_TO_THE_H5_FILE`
* Visualize the model in browser
  * For Python 2 users, `python -m SimpleHTTPServer`
  * For Python 3 users, `python -m http.server`
  * Open localhost:8080 in your browser
  * Most of the predictions should be correct (green) now