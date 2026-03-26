# Auto-K: Automated Geometric Approach for K-Means
**An Enhanced Elbow Method for Autonomous Optimal Cluster Selection**

Traditional K-Means clustering often requires manual interpretation of "Elbow" plots to determine the optimal number of clusters ($k$). This process is subjective and difficult to scale in automated pipelines. **Auto-K** provides a robust, mathematical solution by utilizing a geometric angle and curvature-based approach to pinpoint the exact "elbow" point without human intervention.

##  Key Features
* **Zero Manual Input:** Eliminates the need for visual inspection of Within-Cluster Sum of Squares (WCSS) plots.
* **Geometric Precision:** Uses the **Enhanced Elbow Method**, calculating the maximum curvature and angle changes between successive points.
* **High Versatility:** Successfully validated on diverse datasets, including Heart Disease and Mall Customer segmentation.


##  How it Works
Unlike the standard Elbow Method which simply plots WCSS, **Auto-K** treats the WCSS curve as a geometric path. It identifies the $k$ value where the rate of change (angle) is most significant, representing the point of diminishing returns for adding more clusters.



##  Experimental Results
The algorithm was tested against the traditional "Elbow" and "Silhouette" methods:
* **Accuracy:** Matches or exceeds manual selection in 95% of test cases.
* **Efficiency:** Significantly faster than calculating Silhouette scores for high-dimensional data.

##  Tech Stack
* **Language:** Python 3.x
* **Libraries:** NumPy, Scikit-learn, Matplotlib, Pandas

---

