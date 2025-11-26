# multiple-sclerosis-lesion-segmentation
Deep Learning approaches for MS lesion segmentation using U-Net architecture

# Approcci Deep Learning per la segmentazione di lesioni da Sclerosi Multipla

Implementazione della tesi magistrale su approcci di deep learning per la segmentazione automatica di lesioni da Sclerosi Multipla su immagini MRI.

## Notebooks

Ogni notebook è completamente autocontenuto: include installazione delle dipendenze e download automatico del dataset tramite API Kaggle. È sufficiente aprirlo in Google Colab ed eseguirlo.

- **U-Net 2D**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Alaska-23/multiple-sclerosis-lesion-segmentation/blob/main/unet2d_final.ipynb)
- **U-Net 3D**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Alaska-23/multiple-sclerosis-lesion-segmentation/blob/main/unet3d_final.ipynb)
- **U-Net Multicanale**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Alaska-23/multiple-sclerosis-lesion-segmentation/blob/main/unet2d_multichannel_final.ipynb)

## Utilizzo

1. Clicca sul badge "Open in Colab" del notebook desiderato
2. Esegui tutte le celle sequenzialmente
3. Il dataset verrà scaricato automaticamente e l'addestramento inizierà


## Architetture implementate

- **U-Net 2D**: Segmentazione slice-by-slice su immagini 2D
- **U-Net 3D**: Segmentazione volumetrica completa su volumi 3D
- **U-Net Multicanale**: Integrazione del contesto spaziale tramite slice adiacenti FLAIR

## Citazione
