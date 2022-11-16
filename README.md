# AISD

Acute ischemic stroke dataset contains 397 Non-Contrast-enhanced CT (NCCT) scans of acute ischemic stroke with the interval from symptom onset to CT less than 24 hours. The patients underwent diffusion-weighted MRI (DWI) within 24 hours after taking the CT. The slice thickness of NCCT is 5mm. 345 scans are used to train and validate the model, and the remaining 52 scans are used for testing. Ischemic lesions are manually contoured on NCCT by a doctor using MRI scans as the reference standard. Then a senior doctor double-reviews the labels.

1. Download the image data (image.zip) [[Baidu YUN]](https://pan.baidu.com/s/12nouuU6MbFrQps4EmTcomA) with the password "aisd" or [[Google Drive]](https://drive.google.com/file/d/157f9aE3ZhRSdIuIbP2PRG8ub9JJWvMGk/view?usp=share_link).
2. Download the mask data (mask.zip) [[Baidu YUN]](https://pan.baidu.com/s/1MR4tAEHypdTRnqprXuRRXQ) with the password "aisd" or [[Google Drive]](https://drive.google.com/file/d/1d08fFpEvK4D6YTKfRlNuv_OlIxigZxl6/view?usp=share_link).
3. Download the dicom data (dicom-0.tar.gz)[[Baidu YUN]](https://pan.baidu.com/s/1JLgGtkdzP8TlH2va5LRQ7w) or [[Google Drive]](https://drive.google.com/file/d/1WZdjvq0ZFPnNpbhfxadIYPcbWpdjgM-n/view?usp=share_link), (dicom-1.tar.gz)[[Baidu YUN]](https://pan.baidu.com/s/15CFiAdhI0cG7Ad1GT3gpUQ) or [[Google Drive]](https://drive.google.com/file/d/1CBVHFq8m3-FjG3-aCRfkUMzgHsfheTLd/view?usp=share_link), (dicom-2.tar.gz)[[Baidu YUN]](https://pan.baidu.com/s/1QLOUojfAzFSE3-F8hTJZ7w) with the password "aisd" or [[Google Drive]](https://drive.google.com/file/d/1ZBK93GfTwpfJTv5DlD2vhZnbO5JXpwrz/view?usp=share_link).
4. Four missing dicom files('0091465', '0091468', '0091505', '0091519') can be downloaded from (dicom-3.tar.gz)[[Baidu_YUN]](https://pan.baidu.com/s/1Rblm1fU6xrpYSQub45f-Ig) with the password "aisd" or [[Google Drive]](https://drive.google.com/file/d/1mRKPp9hvMCGb5QVUuCG-ELL-zBiHLxun/view?usp=share_link). Thank yimuu for pointing this out.
5. The data ids in test set are 0073410, 0072723, 0226290, 0537908, 0538058, 0091415, 0538780, 0073540, 0226188, 0226258, 0226314, 0091507, 0226298, 0538975, 0226257, 0226142, 0072681, 0091538, 0538983, 0537961, 0091646, 0072765, 0226137, 0091621, 0091458, 0021822, 0538319, 0226133, 0091657, 0537925, 0073489, 0538502, 0091476, 0226136, 0538532, 0073312, 0539025, 0226309, 0226307, 0091383, 0021092, 0537990, 0226299, 0073060, 0538505, 0073424, 0091534, 0226125, 0072691, 0538425, 0226199, 0226261.

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
