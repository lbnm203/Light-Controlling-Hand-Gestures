# Light Controlling Using Hand Gestures

This project provides a Light Control application using MLP model and hand gesture detection

# Setup - Installation and Usage

**1. Clone the repository**

```
git clone https://github.com/lbnm203/Light-Controlling-Hand-Gestures
cd Light-Controlling-Hand-Gestures
```


**2. Create and Activate Env**

```
conda create -n gesture_env python=3.10.0
conda active gesture_env
```

**3. Install requirements**
```
pip install -r requirements.txt
```

**4. Download/Prepare data**

- Use file ``generate_landmark_data.py`` to collect data
```
python generate_landmark_data.py
```

**5. Training**

- Run file `hand_gesture_recgonition.ipynb` in `notebooks` folder





