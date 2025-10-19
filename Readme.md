# PySpark ML – SMS Spam Detection

End-to-end **PySpark** pipeline for SMS spam classification using TF-IDF + Logistic Regression.
Includes training, evaluation, and single-text prediction with a saved `PipelineModel`.

## 1) Dataset

Use the public **SMS Spam Collection** dataset (UCI).  
- Download from UCI (search “SMS Spam Collection”).
- Make a CSV file with **header** `label,text` where `label` is `ham` or `spam`.
- Save as: `data/raw/sms_spam.csv`

Example (first lines):
```csv
label,text
ham,Go until jurong point, crazy.. Available only in bugis n great world la e buffet...
spam,Free entry in 2 a wkly comp to win FA Cup final tkts 21st May 2005...
