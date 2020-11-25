# SE_project

Tasks Done and their corresponding notebook-
<br>
- [x] Implemented VGG - vgg_cifar_10.ipynb
- [x] Finetuned implemented VGG - SE_ADAM_TEST1.ipynb
- [x] Changed consective 3x3 Conv layers to a single 5x5 Conv layer - vgg_larger_filter.ipynb
- [x] Finetuned the above - SE_5_5optimized.ipynb
- [x] Implemented NIN for VGG:v1 - vgg_cifar_10_exp.ipynb
- [X] Implemented NIN for VGG:v2 - vgg_ninv2.ipynb
<br>
# Set up and more about WandB
We used this free of cost library to capture our training results as well as performance metrics like memory consumption and GPU utilization. [This](https://docs.wandb.com/quickstart) is the link to the documentation of the same. Please create an account with the same before running the notebooks on google Colab. The link to signup is in the documentation in case this [link](https://app.wandb.ai/login?signup=true) doesn't work.
<br>
# Running the Notebooks
This repository is being submitted as a zip file containing all the .ipynb files. Please do run these notebooks on google Colab as we used this environment for our project and it'll ensure smooth running of code.Before running make sure the GPU instance of google Colab is enabled, this can be checked by clicking Edit->Notebook Settings in the toolbar and selecting GPU in the dropdown menu if not already selected. Once on google Colab, all the cells can be run by hitting Runtime->Run all in the tool bar. While running, since we have used WandB to keep track of our experimentation an authentication will be required to connect google Colab to your account you have made above. There will be a link generated on the notebook itself, just log in and entering the authentication key obtained back into the notebook. After which the notebook won't require any other use input. However, if the user wants to execute every cell individually he/she can do so to ny hitting shift+enter keys when on each cell. The dataset is downloaded and pre-processed by the code itself hence this repository contains no dataset. To check the graphical results in real-time go to the Run page on your WandB account. 
