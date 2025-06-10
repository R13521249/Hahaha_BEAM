# Beam Damage Detection Project

此專案旨在使用 **CNN (EfficientNetV2-S)** 和 **YOLOv8** 模型進行樑損傷檢測與分類，並輸出預測結果至 CSV 檔案。

Beam Damage Detection
│
├── dataset_beam/                     # 資料集目錄
│   ├── beam_damage/                  # 訓練用資料集
│   ├── beam_crack/                   # YOLO 訓練資料
│   └── test/                         # 測試資料集
│
├── beam_crack.yaml                   # YOLO 訓練設定檔
├── best_multitask_model.pth          # 預訓練的 CNN 模型檔案
├── runs/detect/yolov8_beam_crack_aug # YOLO 訓練輸出目錄
├── beam_submission.csv               # 最終輸出的預測結果
└── main.py                           # 主程式
