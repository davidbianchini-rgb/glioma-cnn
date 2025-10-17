# glioma-cnn
3D CNN-based pipeline for automatic glioma segmentation and controlled region growing on multiparametric MRI.
Le sequenze da caricare sono:
T1 post-contrasto (csT1W_3D mdc)
FLAIR (3D_ax)
DWI (ADC map)  
CBV (nrCBVcorrLCRegFE_EPI)
Ktrans (RegT1_TFE 3D 65dyn)
APT (10 slices)

Le strutture si devono chiamare: 
MALATO
SANO
RIF
