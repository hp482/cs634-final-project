# Harry Polishook
# cs634-final-project
cs634-final-project


1) Run the 'Check configuration' section to confirm your colab VM is GPU enabled
2) Copy images.zip to the root of your Google Drive.

Once per session or when you reset the Colab vm
1) Run the 'Mount Google Drive to Colab VM' section and authorize Colab to access your goolge drive
2) Run the 'Unzip Images' section to open the zip file and copy the files to the ephemeral VM drive
3) Run the 'Helper Functions' if you intend to use test_model
4) Run the 'Train Model Functions' section
5) Run the 'Model Definitions' section
The 'Work Space' secton is intended for experimentation
As you edit the 'Model Definintions',  you may run train_models(model number, number of epochs) to train a model.  

The Notebook is currently configured for four different models numbered 1-4
After training the resultant weight and model files will be saved to your Google Drive

You may then run test_model(model number) to see a matrix of probabilities and predictions of test images

 



Note:  if initially training or testing fails, it may be due to the presence of hidden ipynb_checkpoints directories.  A second section in 'Unzip Images' will remove them
