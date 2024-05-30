# Heterogeneous Feature Selection Ensemble (HFSE)

In a Heterogeneous Feature Selection Ensemble (HFSE) multiple AI selectors are chosen to be a part of this ensemble as the name implies. These feature selectors in this ensemble vote for the best features using a ranking score. The feature that receives the highest votes is considered the best while the feature with the lowest votes is the least significant. Using a variety of AI models for selecting features is advantageous because it controls the variance, and reduces the likelihood of poor feature selection.


![hfse_fig](https://github.com/ulya-sabeel/HFSE-for-CICIDS2017-Dataset/assets/78443098/09d8a458-49da-4132-863b-332daf68b4a2)




Prerequisites:

Python >=3.6.0

Network Security Dataset Used: CICIDS2017

If you use the above technique for your research, kindly cite it as follows:

Plain text format:

U. Sabeel, S. S. Heydari, K. Elgazzar and K. El-Khatib, "Building an Intrusion Detection System to Detect Atypical Cyberattack Flows," in IEEE Access, vol. 9, pp. 94352-94370, 2021, doi: 10.1109/ACCESS.2021.3093830.

BibTex format:

@ARTICLE{9469900, author={Sabeel, Ulya and Heydari, Shahram Shah and Elgazzar, Khalid and El-Khatib, Khalil}, journal={IEEE Access}, title={Building an Intrusion Detection System to Detect Atypical Cyberattack Flows}, year={2021}, volume={9}, number={}, pages={94352-94370}, keywords={Artificial intelligence;Feature extraction;Training;Benchmark testing;Data models;Computer crime;Network intrusion detection;Artificial Intelligence (AI);atypical attacks;Denial of Service;feature profile;intrusion detection}, doi={10.1109/ACCESS.2021.3093830}}
