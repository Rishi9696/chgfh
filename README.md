Application of TQWT based filter-bank for sleep apnea screening using ECG signals
•	sleep apnea is a disease in which there is the absence of airflow during respiration for at least 10 s. 
•	It may occur several times during the night sleep. 
•	cardiovascular diseases. 
•	 To detect this disease, signals obtained from many channels of polysomnography are to be observed visually by physicians for the long duration.
•	A polysomnogram (PSG), or sleep study, measures a number of variables to assess sleep disturbances: 
•	Electroencephalogram (EEG): Measures brain activity 
•	Electrocardiogram (ECG): Measures heart activity 
•	Pulse oximetry: Measures oxygen saturation 
•	Airflow: Measures nasal and oral airflow 


•	Symptoms include loud snoring, gasping or choking during the night, and morning headaches.
•	procedure is expensive, time-consuming, and subjective. 
•	Hence, it is required to build an automated system to detect the sleep apnea with few channels. 
•	This paper uses single-lead electrocardiogram (ECG) signal to detect apneic and non-apneic events. 
•	The proposed method uses tunable-Q wavelet transform (TQWT) based filter-bank instead of TQWT to decompose the segment of ECG signal into several constant bandwidth sub-band signals. 
•	It is a technique that creates a multiresolution analysis (MRA) with a user-specified Q-factor.
•	Then centered correntropies are computed from the various sub-band signals. The obtained features are then fed to the various classifiers to select the optimum performing classifier. 
•	The measure of similarity normally utilized in statistical signal processing
•	In this work, we have obtained the highest classification accuracy, specificity, and sensitivity of 92.78%, 93.91%, and 90.95% respectively using random forest classifier. 
•	Random forest is that combines the output of multiple decision trees to reach a single result.
 

