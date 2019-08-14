# pm2.5-linear-regression

PM 2.5 prediction
Data source : Central Weather Bureau
Training data : The first 20 days every month
Test data : Random samples from the rest data
Purpose : We like to see the tendency of the PM 2.5 annually, main sources of PM 2.5. 

1. Read data structure, replace 'NR' with 0 
   ( might be useful to discuss 'NR' and discuss whether to discard these parts or any special reason?)
2. Plot correlation plot and see the main pollution sources of PM 2.5.
3. potential direction: I. when? related to air pollutions caused by factories
                        II. which model? linear regression + adagrad, learning rate?
