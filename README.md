# VideoEnhancer
![](assets/ve.png) <BR>

<pre><strong>This is an easy-to-use GUI tools for the open source video enhancement methods.This tools is completely free , 
Just for learning and communication purposes only.</strong></pre>

## 1. User Interface

![](assets/previewer01.png) <BR>
![](assets/previewer02.png) <BR>

## 2. Models.

#### The following models are currently supported, the pre-trained model needs to be downloaded from the official repositories.

 |  Method   | Repo   |
 |  ----  | ----  |
 | A-ESRGAN |https://github.com/aesrgan/A-ESRGAN | 
 | BSRGAN | https://github.com/cszn/BSRGAN |
 | BasicVSRPP  | https://github.com/open-mmlab/mmediting/tree/master/configs/restorers/basicvsr_plusplus |
 | BebyGAN |https://github.com/dvlab-research/Simple-SR | 
 | COMISR |https://github.com/google-research/google-research/tree/master/comisr|
 | EGVSR | https://github.com/Thmen/EGVSR | 
 | ESRGAN | https://github.com/xinntao/ESRGAN |
 | IMDN |  https://github.com/Zheng222/IMDN | 
 | IconVSR | https://github.com/open-mmlab/mmediting/blob/master/configs/restorers/iconvsr/README.md | 
 | OVSR | https://github.com/psychopa4/OVSR | 
 | PPON | https://github.com/Zheng222/PPON | 
 | RSR | https://github.com/BCV-Uniandes/RSR |
 | Real-World-SR |  https://github.com/ManuelFritsche/real-world-sr | 
 | RealBasicVSR | https://github.com/ckkelvinchan/RealBasicVSR | 
 | RealESRGAN | https://github.com/xinntao/Real-ESRGAN | 
 | RealSR |  https://github.com/jixiaozhong/RealSR | 
 | SPSR |  https://github.com/Maclory/SPSR | 
 | SwinIR | https://github.com/JingyunLiang/SwinIR |  
 | TecoGAN | https://github.com/thunil/TecoGAN | 
 | VSR-Transformer | https://github.com/caojiezhang/VSR-Transformer | 
 | *MuCAN |https://github.com/dvlab-research/Simple-SR | 
 | *TecoGAN-PyTorch |https://github.com/skycrapers/TecoGAN-PyTorch |
 | *esrgan-tf2 | https://github.com/peteryuX/esrgan-tf2 | 
 |  |  |
<details>
<summary><b>The ckpts directory structure</b> </summary>
<b>Note:</b> Copy to the appropriate directory, otherwise it will not work properly.<br>
  <pre>
 ----ckpts\
    |----BasicVSRPP\
    |    |----basicvsr_plusplus_ntire_decompress_track1.pth
    |    |----basicvsr_plusplus_ntire_decompress_track2.pth
    |    |----basicvsr_plusplus_ntire_decompress_track3.pth
    |    |----basicvsr_plusplus_reds4.pth
    |    |----basicvsr_plusplus_vimeo90k_bd.pth
    |    |----basicvsr_plusplus_vimeo90k_bi.pth
    |    |----spynet.pth
    |----EGVSR\
    |    |----EGVSR_iter420000.pth
    |----ESRGAN\
    |    |----ESRGAN_SRx4_DF2KOST_official-ff704c30.pth
    |    |----RRDB_ESRGAN_x4.pth
    |----OVSR\
    |    |----ovsr_4x.pth
    |----RealBasicVSR\
    |    |----RealBasicVSR_x4.pth
    |----RealESRGAN\
    |    |----RealESRGANv2-animevideo-xsx2.pth
    |    |----RealESRGANv2-animevideo-xsx4.pth
    |    |----RealESRGAN_x2plus.pth
    |    |----RealESRGAN_x4plus.pth
    |    |----RealESRGAN_x4plus_anime_6B.pth
    |----SPSR\
    |    |----spsr_1x.pth
    |    |----spsr_2x.pth
    |    |----spsr_4x.pth
    |----SwinIR\
    |    |----001_classicalSR_DF2K_s64w8_SwinIR-M_x2.pth
    |    |----001_classicalSR_DF2K_s64w8_SwinIR-M_x3.pth
    |    |----001_classicalSR_DF2K_s64w8_SwinIR-M_x4.pth
    |    |----001_classicalSR_DF2K_s64w8_SwinIR-M_x8.pth
    |    |----002_lightweightSR_DIV2K_s64w8_SwinIR-S_x2.pth
    |    |----002_lightweightSR_DIV2K_s64w8_SwinIR-S_x3.pth
    |    |----002_lightweightSR_DIV2K_s64w8_SwinIR-S_x4.pth
    |    |----003_realSR_BSRGAN_DFOWMFC_s64w8_SwinIR-L_x4_GAN.pth
    |    |----003_realSR_BSRGAN_DFO_s64w8_SwinIR-M_x4_GAN.pth
    |----TecoGAN\
    |    |----TG-2X-TEST.data-00000-of-00001
    |    |----TG-2X-TEST.index
    |    |----TG-4X.data-00000-of-00001
    |    |----TG-4X.index
</pre>
</details>

You can find more ESRGAN models from [Model Database](https://upscale.wiki/wiki/Model_Database).

## 3. Running Environment.

1. The runtime environment is cuda11.1 cudnn8.1.1, Please install and configure it.
2. [LAVFilters-0.75-x64](https://github.com/Nevcairiel/LAVFilters/releases).
3. FFMPEG support is required, copy ffmpeg.exe to the ffmpeg folder.

## 4. Note
1. The execution is less efficient than the command line interface because of the GUI and the prevention of memory overflows.<br>
2. Thanks to all the open source authors this program references, if it is detrimental to your rights, <br>
please let me know and I will remove it as soon as possible.
