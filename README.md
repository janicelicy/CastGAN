# Cast-GAN: Learning to Remove Colour Cast in Underwater Images
<p align="center">
Chau Yi Li*, Andrea Cavallaro</br>
Queen Mary University of London, London, United Kingdom</br>
*chauyi.li@qmul.ac.uk</br>
</p>

## Abstract
Underwater images are degraded by blur and colour cast caused by the attenuation of the illuminant in the water medium. To remove the colour cast with neural networks, images of the scene taken under white illumination are needed as reference for training, but are generally unavailable. As an alternative, one can use surrogate reference images taken close to the water surface or degraded images synthesised from reference datasets. However, the former still suffer from colour cast and the latter generally have limited colour diversity. To address these problems, we exploit open data and typical colour distributions of objects to create a synthetic image dataset that reflects degradations naturally occurring in underwater photography. We use this dataset to train Cast-GAN, a Generative Adversarial Network whose loss function includes terms that eliminate artifacts that are typical in underwater images enhanced with neural networks. We compare the enhancement results of Cast-GAN with four state-of-the-art approaches and validate with a subjective evaluation.

## Testing

- Testing Cast-GAN 
```
python test.py
```

# Citation
If you use the sample code or part of it in your research, please cite the following:

```
@ARTICLE{PrivacyPreserving_Pipeline_Li_Cavallaro_2022,
       author = {{Li}, C.Y. and {Cavallaro}, A.},
        title = "{Training privacy-preserving video analytics pipelines by suppressing features that reveal information about private attributes}",
      journal = {International Conference on Acoustics, Speech, and Signal Processing},
         year = 2022,
        month = May,
}
```

