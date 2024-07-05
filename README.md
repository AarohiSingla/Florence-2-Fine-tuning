### Check this tutorial : 

### Environment setup to run FLorence-2 on Windows:
        pip install torch==2.2.1 torchvision==0.17.1 torchaudio==2.2.1 --index-url https://download.pytorch.org/whl/cu121
        
        pip install transformers
        pip install timm
        pip install packaging
        pip install wheel
        pip install ninja
        pip install flash_attn  # not on windows
  
  #####  Download wheel file from : https://github.com/bdashore3/flash-attention/releases
  pip install flash_attn-2.5.9.post1+cu122torch2.2.2cxx11abiFALSE-cp311-cp311-win_amd64.whl
  
  pip install einops
  pip install accelerate
  pip install peft
  pip install matplotlib


  ### For Dataset Prepration:  Check data_prep.ipynb 

  ### For fine tuning florence2 for object detection task:  fine_tuning_florence2.ipynb
  Fine tuned Trained model is available in model_checkpoints folder

  ### For Inference: test.ipynb

  Output image:

![image](https://github.com/AarohiSingla/Florence-2-Fine-tuning/assets/60029146/4a2d0a8d-de45-4bd6-b31a-18a557c3c8a7)


 
  
