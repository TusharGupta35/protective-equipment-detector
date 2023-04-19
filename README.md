# Protective Equipment Detector
Author: Tushar Gupta <tushartafs2012@gmail.com>

## Instructions to run our model with webcam

1. Setup your virtual environment.
```powershell
python -m venv venv
```

2. Activate your virtual environment. (Assuming you're using powershell)
```powershell
.\venv\Scripts\Activate.ps1
```

3. Setup git submodules.
```powershell
git submodule init
git submodule update
```

4. Install dependencies.
```powershell
pip install -qr .\yolov5\requirements.txt
```

5. Run our model with webcam.
```powershell
python yolov5/detect.py --weights best.pt --img 200 --conf 0.8 --source  0
```
Note: Adjust confidence value according to your needs.
