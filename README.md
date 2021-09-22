# K-Means-Dash-WebApp

### **Background:** 

This project was inspired by the idea to automate unsupervised learning techniques, in particular the Kmeans algorithm.

### **Workflow**

This is a tool that is able to ingest CSV, XLSX, or TXT data and provide a automated segmentation based on the users selection of (N) clusters. The workflow is below:


  1. Browse for a file (CSV, XLSX, or TXT) and import the data (the data is displayed pre-standardized by utilizing Min-Max Scaling)
  2. Once navigated to the 'Kmeans Exploration' tab, you can input a range of chosen clusters to examine the optimal amount of clusters, which is visualized by an Elbow Plot
  3. Once navigated to the 'Kmeans Prediction' tab, you can select the amount of clusters you'd like to segment your data by


### **Output**

Once all of the steps mentioned above have been executed, the datatable in the 'Kmeans Prediction' tab should update with the original data prior to standardization, with an additional column which shows the cluster each datapoint has been assigned. Additionally, there is a chart, which populates that visualizes the segmentation of your data in 2D space.


### **Caveat**

This is still a Work-in-progress - the aesthetics will be updated at a later time.
