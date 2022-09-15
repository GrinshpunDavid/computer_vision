## Project description:
Aim of the project is to determine the age of the subject form his portrait picture.

### Data description:
- 7.6k photos
- The labels.csv file with two labels columns: file_name and real_age

### Goal:
The MAE metric on the test set should not be more than 8.

### Steps performed:
- Exploratory Data Analysis
- Preprocessing image using ImageDataGenerator
- train/test split
- Model = Sequential , backbone = ResNet50, optimizer = Adam

### Results:
- Test MAE: 7.1773
