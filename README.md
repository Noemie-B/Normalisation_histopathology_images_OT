# Normalisation_histopathology_images_OT

1. Code for patches creation : https://nbviewer.org/github/afiliot/TPDUIA/blob/main/TPDUIA/2022/whole_slide_images.ipynb
2. Normalisation  
   a. For Vahadane, Macenko, Reinhard and Ruifrok methods : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/2-Normalization_Reinhard_Vahadane_Macenko_Ruifrok.ipynb
      Code from tiatoolbox : https://github.com/TissueImageAnalytics/tiatoolbox
   b. Our implementation with GeomLoss : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/2_Normalization_Geomloss.ipynb
      GeomLoss package : https://www.kernel-operations.io/geomloss/_auto_examples/optimal_transport/plot_optimal_transport_color.html#sphx-glr-auto-examples-optimal-transport-plot-optimal-transport-color-py
   c. Normalisation with StainGAN and StainNET : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/2_Normalization_StainGAN_StainNET.ipynb
      Code for StainGAN and StainNET : https://github.com/khtao/StainNet/tree/master
3. Nuclei segmentation and classification with HoVer-Net (PanNuke weights) : https://github.com/simongraham/hovernet_inference/tree/master/hover
4. Metrics for methods comparison :
   a. Nuclei segmentation and classification scores : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/3_Metrics_nucleus_segmentation_classification_scores.ipynb
   b. Quality images score : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/3_Metrics_Quality_images_score.ipynb
   c. Patches classification : https://github.com/Noemie-B/Normalisation_histopathology_images_OT/blob/main/3_Metrics_DL_Classification_datasets.ipynb
