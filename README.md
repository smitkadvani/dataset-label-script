# Dataset-label-script

## 1. Convert video to images 
`ffmpeg -i 20240305_140703.mp4 -vf fps=20 out1%d.jpg`

## 2. Labeel images 
### Download labelImg tool 
`pip install labelImg`

## 3. Execute labelImg command and there you go with UI
<img width="690" alt="image" src="https://github.com/smitkadvani/dataset-label-script/assets/26624253/ce72b45c-eb4c-4f54-9397-8a2144b47861">

## 4. Finish model selection default: YOLO.
