# MobileSensingAndHealth
*Repository for a Fluid Consumption Classifier and Estimator*

## Data Collection
####  Hardware
- Audio Data will be collect by the 3 collaborators using a [AV-JEFE TR-15 Throat Transdermal Microphone for Speech Difficulties](https://www.superaudioworld.com/product-page/av-jefe-tr-15-throat-transdermal-microphone-for-speech-difficulties) and stored as digital audio files in the lossless Waveform Audio File format (.wav) format
#### Activities Collected
1. Drink: 20 samples for each volume (5, 10, 15, 20)mL
2. Eat: 40 samples each of random eating events
3. Talk: 40 samples each of random talking events
4. Breathe: 40 samples each of random breathing events
#### Naming Convention
- {Initials} _ {Activity&Amount(mL)} _ {Sample #}
- ex. *TD_Drink_20.wav* 




## Files
1. FC_Classifier.py: 
The classifier classifies audio signals into drinking and non-drinking events
2. FC_Estimator.py: 
The estimator estimates the volume of fluid consumed during drinking events

## Modules and Packages
- [librosa](https://pypi.org/project/librosa/): A python package for music and audio analysis 
- [NumPy](https://numpy.org/): A python library for working with arrays
- [pandas](https://pandas.pydata.org/): A python library for data analysis and manipulation 
- [scikit-learn (sklearn)](https://scikit-learn.org/stable/): A python library for machine learning
- [Matplotlib](https://matplotlib.org/): A python library for plotting
- [SciPy](https://www.scipy.org/): A python library for scientific computing
- [keras](keras.io): A python library for deep learning frameworks


## Limitations
- Limited sample size
- Varying data collection software (potentially varying sample sizes)
- Carbonated beverages?
- Drinking speed

