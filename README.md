
# RSNA Pneumonia Detection dataset

The training dataset (both of the csv files and the training image folder) contains information of 26684 patients (unique) Out of these 26684 unique patients some of these have multiple entries in the both of the csv files.  20672 patients belong to Target = 0 (No Pneumonia) 6012 patients have a bounding box (Target = 1). The classes "No Lung Opacity / Not Normal" and "Normal" is associated with Target = 0 whereas "Lung Opacity" belong to Target = 1

The images are present in dicom format, from which information like PatientAge, PatientSex, ViewPosition etc are obtained There are two ways from which images were obtained: AP and PA. The age ranges from 1-155 (which were further clipped to 100) The centers of the bounding box are spread out over the entire region of the lungs. But there are some centers which are outliers.
