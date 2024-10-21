# ML

# Dataset Description

The Healthy Brain Network (HBN) dataset is a clinical sample of about five-thousand 5-22 year-olds who have undergone both clinical and research screenings. The objective of the HBN study is to find biological markers that will improve the diagnosis and treatment of mental health and learning disorders from an objective biological perspective. Two elements of this study are being used for this competition: physical activity data (wrist-worn accelerometer data, fitness assessments and questionnaires) and internet usage behavior data. The goal of this competition is to predict from this data a participant's **Severity Impairment Index (sii)**, a standard measure of problematic internet use.

**Note:** This is a Code Competition, in which the actual test set is hidden. In this public version, we give some sample data in the correct format to help you author your solutions. The full test set comprises about 3800 instances.

The competition data is compiled into two sources, **parquet** files containing the accelerometer (actigraphy) series and **csv** files containing the remaining tabular data. The majority of measures are missing for most participants. In particular, the target **sii** is missing for a portion of the participants in the training set. You may wish to apply non-supervised learning techniques to this data. The **sii** value is present for all instances in the test set.
