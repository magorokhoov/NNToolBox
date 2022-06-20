# Toolbox4nn
Toolbox4nn is PyTorch framework for research and developing. Priority is CV (classification, super-resolution, stylization,  

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


This project was heavily inspired by [traiNNer](https://github.com/victorca25/traiNNer) (developed by [victorca25](https://github.com/victorca25))
