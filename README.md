# AISD

Acute ischemic stroke dataset contains 397 Non-Contrast-enhanced CT (NCCT) scans of acute ischemic stroke with the interval from symptom onset to CT less than 24 hours. The patients underwent diffusion-weighted MRI (DWI) within 24 hours after taking the CT. The slice thickness of NCCT is 5mm. 345 scans are used to train and validate the model, and the remaining 52 scans are used for testing. Ischemic lesions are manually contoured on NCCT by a doctor using MRI scans as the reference standard. Then a senior doctor double-reviews the labels.

1. Download the image data (image.zip) [[Baidu YUN]](https://pan.baidu.com/s/12nouuU6MbFrQps4EmTcomA) with the password "aisd".
2. Download the mask data (mask.zip) [[Baidu YUN]](https://pan.baidu.com/s/1MR4tAEHypdTRnqprXuRRXQ) with the password "aisd".
3. Download the dicom data (dicom-0.tar.gz)[[Baidu YUN]](https://pan.baidu.com/s/1JLgGtkdzP8TlH2va5LRQ7w), (dicom-1.tar.gz)[[Baidu YUN]](https://pan.baidu.com/s/15CFiAdhI0cG7Ad1GT3gpUQ), (dicom-2.tar.gz)[[Baidu YUN]](https://pan.baidu.com/s/1QLOUojfAzFSE3-F8hTJZ7w) with the password "aisd".
4. Four missing dicom files('0091465', '0091468', '0091505', '0091519') can be downloaded from (dicom-3.tar.gz)[[Baidu_YUN]](https://pan.baidu.com/s/1Rblm1fU6xrpYSQub45f-Ig) with the password "aisd". Thanks yimuu for pointing this out.

![Samples](https://github.com/GriffinLiang/AISD/blob/main/vis.png)


## Citation

If you use this code, please cite the following paper(s):

	@inproceedings{liang2021SymmetryEnhancedAN,
		title={Symmetry-Enhanced Attention Network for Acute Ischemic Infarct Segmentation with Non-Contrast CT Images},    
		author={Kongming Liang, Kai Han, Xiuli Li, Xiaoqing Cheng, Yiming Li, Yizhou Wang, and Yizhou Yu},    
		booktitle={MICCAI},    
		year={2021}    
	}


## License
This dataset is made freely available to academic and non-academic entities for non-commercial purposes such as academic research, teaching, scientific publications, or personal experimentation.
