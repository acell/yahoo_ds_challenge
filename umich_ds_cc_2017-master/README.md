# Challenge description

In this challenge, you will be provided with two sets of audio clips: one where the instrument being played in the clip is known, and one where the instrument being played is unknown. It is your task to predict, using a machine learning model, which instrument is being played in each of the unknown clips.

# Evaluation criteria

We will be evaluating your performance based on several criteria:

- **Prediction accuracy** -- of course, the primary task is to correctly predict the instrument being played. As such, your prediction accuracy (`n_correct/n_total`) will be a major factor.
- **Expected accuracy match** -- in addition to having high prediction accuracy, reporting an accurate expected accuracy is important as well. We will evaluate how close your prediction of your model's accuracy lines up with your model's true accuracy (`abs(predicted_accuracy - observed_accuracy)`).
- **Code quality and design choices** -- we won't only be looking at your objective performance. We also want to evaluate your thought process and coding style, so we'll be reviewing your code and design choices with respect to feature engineering and model selection.

# Submission process

The unknown music samples will not be available to you from the beginning.  
Once 4 hours has elapsed, we will release the test set publicly via Git/Google Drive/Dropbox for all to access freely.

Please submit your predictions as a csv file with 2 columns, filename and prediction. Please name the file `your_name.csv`, and do not include the column names in the submission. 

**Email this file to rmuraglia@oath.com, jedc@oath.com and yugan@oath.com**.  
In the body of the email please include your anticipated prediction accuracy (e.g. 72.5%).  
Please also put your code in a github repo, and provide a link in your email for us to review your code.

Here is an example of what a submission should look like:

```
Unknown_001.wav,BassClarinet
Unknown_002.wav,BassTrombone
Unknown_003.wav,BbClarinet
Unknown_004.wav,Cello
Unknown_005.wav,EbClarinet
Unknown_006.wav,Marimba
Unknown_007.wav,TenorTrombone
Unknown_008.wav,Viola
Unknown_009.wav,Violin
Unknown_010.wav,Xylophone
...
Unknown_131.wav,Cello
```

The only possible values for the instrument labels are: "BassClarinet", "BassTrombone", "BbClarinet", "Cello", "EbClarinet", "Marimba", "TenorTrombone", "Viola", "Violin" and "Xylophone". Please ensure that your labels match these. Examples of invalid labels are "Bass Clarinet" and "bassclarinet".

Upon receipt of a properly formatted submission to rmuraglia@oath.com, we will record your performance metrics, but will not inform you of your performance until submissions are closed.

You are encouraged to submit early, and to resubmit as you refine your model. Only your final submission's scores will be considered in the rankings, so please don't hesitate to submit a coarse model. Get on the leader board with something complete, and then work to improve it with your remaining time.

Good luck!
