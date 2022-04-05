# california-school-analysis

## Current Roadmap

# Overview of Data
  - The California Department of Education offers data on the following categories:
      * Absenteeism
      * Accountability
      * Annual Enrollment
      * Assessment
      * CALPADS Unduplicated Pupil Count (UPC)
      * CBEDS School/District Information
      * Discipline
      * District of Choice
      * Graduate and Dropout
      * Post-Secondary Enrollment
      * Private Schools Data
      * Public School and District
      * Stability Rate Data
      * Staff and Course Enrollment
  - We plan to focus on stricly high school data.

# Creating the dataset/Preprocessing
  - n by m array where n = the number of schools and m = number of school features. The features will be drawn from each dataset and joined by school.
  - Normalize and scale all data 

# Dimensionality Reduction
  - Principal Component Analysis

# Unsupervised Clustering
  - Cluster schools using K-Means (or the like)
  - Analyze why certain schools where clustered together
  - Determine optimal number of clusters to use 

# Supervised Learning of School Performance
  - Design custom objective function that measures student performance/school performance/etc. ???
  - Use a supervised model on each cluster, using school performance metric as labels.
  - Feature importance analysis: What caused rises in school performance increases/decreases by cluster?
