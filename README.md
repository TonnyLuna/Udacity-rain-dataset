# Udacity-rain-dataset
### By Antonio Luna-Álvarez and Dante Mújica-Vargas

This repository shares the dataset created for the article titled "Convolutional Neural Network and Filtering for Rain and Fog Suppression in Driving Images." This dataset includes 1,180 driving images from the Udacity simulator, modified to include five rain masks with their respective ground truth, to experiment with removing artifacts that could alter the visibility of an automated driving model without affecting image quality.

##Image examples

![Rainy image mask 1](rainy_image/0_1.jpg)
![Ground truth](ground_truth/0.jpg)

![Rainy image mask 5](rainy_image/1000_5.jpg)
![Ground truth](ground_truth/1000.jpg)

The repository content is located in Git LFS, so it must be downloaded using:

```
git clone --recurse-submodules https://github.com/TonnyLuna/Udacity-rain-dataset.git
cd Udacity-rain-dataset/
git lfs pull

```


## Citation
We appreciate citing our work in your publications


```
@article{perez2019construccion,
  title={Red Neuronal Convolucional y de Filtrado para la Supresi{\'o}n de Lluvia y Niebla en Im{\'a}genes de Conducci{\'o}n
  author={Luna-{\'A}lvarez, A and M{\'u}jica-Vargas, D},
  journal={Jornada de Ciencia y Tecnolog{\'\i}a Aplicada Tecnol{\'o}gico Nacional de M{\'e}xico/CENIDET},
  volume={2},
  pages={28--32},
  year={2019}
}
```

## License

**Free Software**

