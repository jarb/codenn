# Assignment
* extract Java methods names from `JetBrains/intellij-community`
* get a CodeT5+ network
* adapt CodeT5+ to predict method name by its (masked) text
* estimate quality (CER, editdist, accuracy, BLEU) of prediction
* fine-tune the model on Java code from the repo
* measure metrics enhancement after fine-tuning

# How to
* all the requirements, code and results are stored in IPython notebook
* there are shortcuts to start from certain stage with already prepared artefacts from GDrive
* notebook was tested and infered in Google Colab

# System info
Everything was tested in GColab with 1 V100 GPU (16Gb VRAM), 14 Gb RAM and 50 Gb disk.
