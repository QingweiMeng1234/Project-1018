# Project-1018
Hi this is a DEV branch
Team members:
Chris Chen
Kanika Agarwal
Weber Meng

CC_ACE_Analysis:
1. CC_ACE_Preprocessing_time_gaps_nans_V1.ipynb: Preprocess ACE by finding NaNs and gaps
2. CC_ACE_ARIMA.ipynb: Run an ARIMA on ACE (do preprocessing first)

GenMixAnalysis:
GenFuelMixAnalysisV1 to V3: Demonstration of proof-of-concept basic ARIMA and Kalman on Gen Fuel Mix. Use V3.
1. CC_GenFuelMix_Kalman.ipynb: Preprocess Gen Fuel Mix. Run attempts at Kalman Filters on Gen Fuel Mix.
GenMix_nanremoved.pkl - pickled preprocessed Gen Fuel Mix all data
GenMix_Consolidated.pkl - pickled Gen Fuel Mix group by 5 major fuel types
CGS_2Latent_KF.pkl - pickled pykalman Kalman Filter object for saving KF Model with 2 latents for 3 observed (Coal/Gas/Wind) model.
I will try more Kalman Filters.




