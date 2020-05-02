## Shadow Removal

## Networks (Results)
- Unet,MSEFlat
    - Hmm Good mostly. Not that great for validation set
- Unet,L1Leoss, Adam
    - Okay ish
- Unet, SGD, L1Loss
    - Slow...
    - didnt even do that well
- Unet, AdamW, L1Loss
    - fassst
    - best so far
## Conclusion
- AdamW ftw
- L1Loss sometimes does better than MSE

-![img](shadow.jpg)