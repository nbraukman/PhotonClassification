# Classify Prompt and Fake Photons with Keras
**Main notebooks:**

`LoadData.ipynb`: Load MC and data with a Coffea Processor. Scale MC according to luminosity of dataset.

`PhotonClassification.ipynb`: Preprocess output from the Coffea Processor for use in machine learning. Build, train, evaluate the Keras model.

---

**To Do:**

* Resolve issue filling a Coffea histogram with the output of Keras' `model.predict()` in order to analyze systematic errors.
