# CoronaML
THIS MACHINE LEARNING SCRIPT ATTEMPTS TO DEVELOP THE DEEP LEARNING MODEL IN KERAS WITH TENSOR FLOW IN BACKEND TO PREDICT THE NUMBER OF CONFIRMED CORONA VIRUSS CASE WITH PRECIPITATION AND TEMPERATURE AS THE INPUTS. THE MODEL TAKES DATA FROM NOAA WHICH USES 9000 EARTH STATION TO RECORD DAILY TEMPERATURE AND PRESIPITATION. TEMPERATURE DATA ARE IN TENTH OF CENTIGRADE WHILE PRESPITATION IS ALSO IN TENTH OF MM. MEANWHILE THE COVID CASE FROM JAN 2) ONWARDS ARE ONLY CONSIDERED.

THE MODEL USES RELU AS ACTIVATION FUNCTION AND ADAM ALGORITHM AS OPTIMIZER WITH MEAN_SQUARE_ERROR AS LOSS FUNCTION. SINCE MACHINE LEARNING DOESN"T GIVE CAUSATION THIS MODEL IN NO MEAN IMPLIES THERE IS RELATION BETWEEN TEMPERATURE AND PRESIPITATION ON COVID-19 CASES

MAJOR LIMITATION OF THE MODEL IS IT DOESN"T CONSIDER THE STATEWISE DATA FROM US,AND AUSTRALIA

NOAA DATA CAN BE RETRIEVE IN R USING WORLDMET DATA. THE BEST PAPER TO EXPLAIN THIS IS FROM RECENT MIT PAPER Bukhari, Q., & Jameel, Y. (2020). Will coronavirus pandemic diminish by summer?. Available at SSRN 3556998. THE TRAINING HOWEVER DOESN'T SHOW CONVERGENCE

# THE KERAS MODELING IS DONE IN GOOGLE COLAB

https://colab.research.google.com/drive/1EsFYtx-miAOHBAfKcULIkAVrBO2nRehm
