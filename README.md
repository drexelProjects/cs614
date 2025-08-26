# AI-Enhanced Emergency Response System: Literature and Market Review

### [Pipeline Demo](emergency_stroke_pipeline.ipynb)

We have integrated the models into a working demo system, with audio and vitals ingestion, preprocessing, classification, and visualization.

### [Vitals Classifier](vitals.ipynb)
Using a Random Forest baseline, we achieved preliminary classification accuracy on synthetic and public vital-sign datasets. The model outputs feature attributions via SHAP values, which allow clinicians to interpret which physiological features (e.g., elevated blood pressure, oxygen desaturation) contributed most to a given prediction.

### [Speech Model](dysarthriaDetection.ipynb)
For audio-based detection, we developed a prototype using Wav2Vec2 embeddings with an attention-based neural network classifier. Early experiments on dysarthric/stroke-like speech corpora indicate that the model can capture prosodic and phonetic cues relevant to stroke. We visualize attention heatmaps over time and model confidence trajectories, illustrating the interpretability of predictions and potential for real-time monitoring during emergency calls. 
