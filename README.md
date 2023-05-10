# Project 5: Traffic

## Short Video: 

## programming by:
- Reza Nasirzadeh Ezmareh


## Description:
<h1 tabindex="-1" dir="auto"><a id="user-content-traffic" class="anchor" aria-hidden="true" href="#traffic"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Traffic</h1>
<p dir="auto">An AI that uses Tensorflow to train a convolutional neural network to identify which traffic sign appears in a photograph</p>
<h2 tabindex="-1" dir="auto"><a id="user-content-background" class="anchor" aria-hidden="true" href="#background"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Background</h2>
<p dir="auto">As research continues in the development of self-driving cars, one of the key challenges is computer vision, allowing these cars to develop an understanding of their environment from digital images. In particular, this involves the ability to recognize and distinguish road signs – stop signs, speed limit signs, yield signs, and more</p>
<p dir="auto">The dataset that will be used is the <a href="https://benchmark.ini.rub.de/?section=gtsrb&amp;subsection=news" rel="nofollow">German Traffic Sign Recognition Benchmark (GTSRB)</a> dataset, which contains thousands of images of 43 different kinds of road signs</p>
<h2 tabindex="-1" dir="auto"><a id="user-content-files" class="anchor" aria-hidden="true" href="#files"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Files</h2>
<p dir="auto">The dataset is too large, therefore the <code>data</code> directory only contains the links to download them. After downloading, the <code>data</code> directory should be replaced by the downloaded folder, namely "gtsrb". The <code>traffic.py</code> file contains the main functions including loading data, getting model, training the model and evaluating the model</p>
<h2 tabindex="-1" dir="auto"><a id="user-content-how-to-use" class="anchor" aria-hidden="true" href="#how-to-use"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>How to Use</h2>
<p dir="auto">Make sure <code>Tensorflow</code>, <code>opencv-python</code> and <code>scikit-learn</code> are installed. If not, run the following command</p>
<p dir="auto"><code>pip install tensorflow opencv-python scikit-learn</code></p>
<p dir="auto">In the <code>traffic</code> directory, run the command</p>
<p dir="auto"><code>python traffic.py data model_filename</code></p>
<p dir="auto">Where <code>data</code> should be either gtsrb or gtsrb-small which are downloaded through the links in the <code>data</code> directory. <code>Model_filename</code> is an optional argument that will store the trained model to the specifiled path</p>
<h2 tabindex="-1" dir="auto"><a id="user-content-example-output" class="anchor" aria-hidden="true" href="#example-output"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Example Output</h2>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>$ python traffic.py gtsrb
Epoch 1/10
500/500 [<span class="pl-k">==============================</span>] - 5s 9ms/step - loss: 3.7139 - accuracy: 0.1545
Epoch 2/10
500/500 [<span class="pl-k">==============================</span>] - 6s 11ms/step - loss: 2.0086 - accuracy: 0.4082
Epoch 3/10
500/500 [<span class="pl-k">==============================</span>] - 6s 12ms/step - loss: 1.3055 - accuracy: 0.5917
Epoch 4/10
500/500 [<span class="pl-k">==============================</span>] - 5s 11ms/step - loss: 0.9181 - accuracy: 0.7171
Epoch 5/10
500/500 [<span class="pl-k">==============================</span>] - 7s 13ms/step - loss: 0.6560 - accuracy: 0.7974
Epoch 6/10
500/500 [<span class="pl-k">==============================</span>] - 9s 18ms/step - loss: 0.5078 - accuracy: 0.8470
Epoch 7/10
500/500 [<span class="pl-k">==============================</span>] - 9s 18ms/step - loss: 0.4216 - accuracy: 0.8754
Epoch 8/10
500/500 [<span class="pl-k">==============================</span>] - 10s 20ms/step - loss: 0.3526 - accuracy: 0.8946
Epoch 9/10
500/500 [<span class="pl-k">==============================</span>] - 10s 21ms/step - loss: 0.3016 - accuracy: 0.9086
Epoch 10/10
500/500 [<span class="pl-k">==============================</span>] - 10s 20ms/step - loss: 0.2497 - accuracy: 0.9256
333/333 - 5s - loss: 0.1616 - accuracy: 0.9535</pre><div class="zeroclipboard-container position-absolute right-0 top-0">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn js-clipboard-copy m-2 p-0 tooltipped-no-delay" data-copy-feedback="Copied!" data-tooltip-direction="w" value="$ python traffic.py gtsrb
Epoch 1/10
500/500 [==============================] - 5s 9ms/step - loss: 3.7139 - accuracy: 0.1545
Epoch 2/10
500/500 [==============================] - 6s 11ms/step - loss: 2.0086 - accuracy: 0.4082
Epoch 3/10
500/500 [==============================] - 6s 12ms/step - loss: 1.3055 - accuracy: 0.5917
Epoch 4/10
500/500 [==============================] - 5s 11ms/step - loss: 0.9181 - accuracy: 0.7171
Epoch 5/10
500/500 [==============================] - 7s 13ms/step - loss: 0.6560 - accuracy: 0.7974
Epoch 6/10
500/500 [==============================] - 9s 18ms/step - loss: 0.5078 - accuracy: 0.8470
Epoch 7/10
500/500 [==============================] - 9s 18ms/step - loss: 0.4216 - accuracy: 0.8754
Epoch 8/10
500/500 [==============================] - 10s 20ms/step - loss: 0.3526 - accuracy: 0.8946
Epoch 9/10
500/500 [==============================] - 10s 21ms/step - loss: 0.3016 - accuracy: 0.9086
Epoch 10/10
500/500 [==============================] - 10s 20ms/step - loss: 0.2497 - accuracy: 0.9256
333/333 - 5s - loss: 0.1616 - accuracy: 0.9535" tabindex="0" role="button" style="display: inherit;">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon m-2">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none m-2">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-test-result" class="anchor" aria-hidden="true" href="#test-result"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>Test Result</h2>
<ul dir="auto">
<li>Different numbers of convolutional and pooling layers</li>
<li>Different numbers and sizes of filters for convolutional layers</li>
<li>Different pool sizes for pooling layers</li>
<li>Different numbers and sizes of hidden layers</li>
<li>Dropout</li>
</ul>
<table>
<thead>
<tr>
<th align="center"></th>
<th align="center">Model</th>
<th align="center">Testing accuracy</th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">1</td>
<td align="center">In Class Model (Base)</td>
<td align="center"><code>0.0531</code></td>
</tr>
<tr>
<td align="center">2</td>
<td align="center">Additional Convolution Layer after Pooling Layer</td>
<td align="center"><code>0.9659</code></td>
</tr>
<tr>
<td align="center">3</td>
<td align="center">Additional Convolution Layer before Pooling Layer</td>
<td align="center"><code>0.9780</code></td>
</tr>
<tr>
<td align="center">4</td>
<td align="center">Additional Max-Pooling Layer</td>
<td align="center"><code>0.0539</code></td>
</tr>
<tr>
<td align="center">5</td>
<td align="center">Modify Pool Size to 3x3 Compare to Model 3</td>
<td align="center"><code>0.9809</code></td>
</tr>
<tr>
<td align="center">6</td>
<td align="center">Modify Filter Size to 4x4 Compare to model 3</td>
<td align="center"><code>0.9546</code></td>
</tr>
<tr>
<td align="center">7</td>
<td align="center">Modify Pool Size to 3x3 Compare to model 2</td>
<td align="center"><code>0.9463</code></td>
</tr>
<tr>
<td align="center">8</td>
<td align="center">Additional Hidden Layer Compare to Model 2</td>
<td align="center"><code>0.9341</code></td>
</tr>
<tr>
<td align="center">9</td>
<td align="center">Modify Hidden Layer to NUM_CATEGORIES * 128 Compare to model 2</td>
<td align="center"><code>0.9345</code></td>
</tr>
<tr>
<td align="center">10</td>
<td align="center">Modify Drop Out Rate to 0.1 Compare to model 3</td>
<td align="center"><code>0.9764</code></td>
</tr>
<tr>
<td align="center">11</td>
<td align="center">Modify Drop Out Rate to 0.2 Compare to model 3</td>
<td align="center"><code>0.9647</code></td>
</tr>
<tr>
<td align="center">12</td>
<td align="center">Modify Drop Out Rate to 0.3 Compare to model 3</td>
<td align="center"><code>0.9655</code></td>
</tr>
</tbody>
</table>
<ul dir="auto">
<li>If not explicitly specified, model changes are comparing to the base model</li>
</ul>
<p dir="auto">Based on the test results, it can be concluded that the base model which only has one convolution layer, one pooling layer and a MNN performs this specific task poorly with accuracy of 0.0531. A better approach is by adding another convolution layer right after the first one and before the pooling layer which boosts the accuracy score to 0.9780. According to model 4, adding a pooling layer to the base model will not perform well. By adjusting the parameters based on model 3, the final result is maximized when modifying the pool size from 2x2 to 3x3, which scored at 0.9809</p>




### Installation-
1] Star and clone the repository to your machine.
2] install `python v3.x`
3] Run the command `pip install -r requirements.txt`
