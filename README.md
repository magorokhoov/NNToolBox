# Toolbox4nn
Toolbox4nn is PyTorch framework for research and developing. Priority is CV (classification, super-resolution, stylization, restoration, GAN, etc) but i think you can use it for NLP also.

*In near future I will make awesome readme and docs*

## Project Structure

```
.
├── experiments -- here will be your reslt of experiments (logs, model weights, val_images, etc) 
└── src -- main code
    ├── data -- datasets and dataloaders
    ├── modules -- losses, models, optimizers, schedulers, metrics (not implemented now), etc
    ├── options -- YAML confings for flexible, powerful and easy configuration
    ├── sh -- sh files start if you use linux like me
    ├── train.py -- main file
    └── utils -- useful stuff like loggers, nicer_timer, dict2str, etc
```


This project was heavily inspired by [traiNNer](https://github.com/victorca25/traiNNer) (developed by [victorca25](https://github.com/victorca25)). Try this one. They are also have a great Discord server "Enchance Everything". You will find link in victorca25 rep.
