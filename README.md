# Normalisation_histopathology_images_OT

1. Code for patches creation : https://nbviewer.org/github/afiliot/TPDUIA/blob/main/TPDUIA/2022/whole_slide_images.ipynb
2. Normalisation  
   a.
      - For Vahadane, Macenko, Reinhard and Ruifrok methods : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/2-Normalization_Reinhard_Vahadane_Macenko_Ruifrok.ipynb  
      - Code from tiatoolbox : https://github.com/TissueImageAnalytics/tiatoolbox  
   b. 
      - Our implementation with GeomLoss : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/2_Normalization_Geomloss.ipynb
      - GeomLoss package : https://www.kernel-operations.io/geomloss/_auto_examples/optimal_transport/plot_optimal_transport_color.html#sphx-glr-auto-examples-optimal-transport-plot-optimal-transport-color-py
   c. 
      - Normalisation with StainGAN and StainNET : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/2_Normalization_StainGAN_StainNET.ipynb
      - Code for StainGAN and StainNET : https://github.com/khtao/StainNet/tree/master
4. Nuclei segmentation and classification with HoVer-Net (PanNuke weights) : https://github.com/simongraham/hovernet_inference/tree/master/hover
5. Metrics for methods comparison :  
   a. Nuclei segmentation and classification scores : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/3_Metrics_nucleus_segmentation_classification_scores.ipynb  
   b. Quality images score : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/3_Metrics_Quality_images_score.ipynb  
   c. Patches classification : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/3_Metrics_DL_Classification_datasets.ipynb  

## Environment

Python version : 3.9.7

For HoVer-Net, please use the environment : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/environment_hovernet_pytorch.yml

For GeomLoss, a specific environment with keops package is used : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/environment_geomloss.yml

For the other, please refer to tiatoolbox and StainNET githubs.


## Disclaimer
The results and analyses presented in this repository are intended for research purposes only. They are not validated for clinical use and should not be used to diagnose, treat, or manage any health conditions. Always consult with a qualified healthcare professional for medical advice and treatment.

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/'>http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is distributed under the the terms of the creative commons attribution <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/'>http://creativecommons.org/licenses/by-nc-sa/4.0/">Licence Creative Commons Attribution - No commercial use - shared in the same conditions 4.0 International</a>.

## Copyright (c) 

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
