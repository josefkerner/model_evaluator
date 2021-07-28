# Framework for generic model training and evaluation
Framework for training and automatic evalutation of various models just based on JSON configurations

Often times, when some real life problems which are being modeled by machine learning models, the feature set and model settings change a lot and fast.
Therefore its beneficial to have a flexible framework, which can quickly train models with various datasets and training settings and evaluate the results again each other, to quickly see which combination of feature set and model settings works the best.

On top of that, framework contains also automatical data preparation pipeline, which is fully customizable by JSON configurations.

So basically, the framework allows user to quickly search the best combination accross the entire model search space ( feature set, data preparation steps, model parameters)

Once the best configuration is selected, it can be easily reused during the production scoring process.
