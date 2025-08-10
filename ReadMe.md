# Self Driving Cars State Estimation and Localization

![Self Driving Cars Localization](media/cover.png)


## Run the filter:
    ```bash
    python3 es_ekf.py
    ```

## 📊 Results
### 🔹 Ground Truth Trajectory
![Ground Truth Trajectory](plots/pt1_GT.png)

### 🔹 Ground Truth vs Estimated Trajectory (Part 1)

![Part 1 Estimated Trajectory](plots/pt1_ET.png)

### 🔹 Error Plots (Part 1)

![Part 1 Error Plots](plots/pt1_error_analysis.png)

---

### 🔹 Ground Truth vs Estimated Trajectory (Part 2)

![Part 2 Estimated Trajectory](plots/pt2_ET.png)

### 🔹 Error Plots (Part 2)

![Part 2 Error Plots](plots/pt22_error_analysis.png)

> Replace the above image paths with your actual plot file locations inside the `plots/` folder.

## ⚙️ Sensor Variance Settings

You can tune the sensor variances inside `main.py` under the **Constants** section:
```python
var_imu_f = 0.1
var_imu_w = 1.0
var_gnss  = 0.01
var_lidar = 0.25
