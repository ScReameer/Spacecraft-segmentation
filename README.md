# <center>Сегментация космических аппаратов
<img src='./imgs/preview.png'></img>

Датасет был взят из [<b>репозитория</b>](https://github.com/Yurushia1998/SatelliteDataset)

В качестве модели для файн-тюнинга использовалась [<b><i>YOLOv8l-seg</b></i>](https://docs.ultralytics.com/tasks/segment/)

Обучение производилось на 50-ти эпохах, в результате были получены следующие метрики:
* $\text{mIoU} \approx 0.84$
* $F_1 \text{-score} \approx 0.66 \text{ at threshold 0.35}$
* $\text{mAP}@50 \approx 0.62$
* $\text{mAP}@(\text{50-95}) \approx 0.47$

Пример предсказаний обученной модели:

<img src='./imgs/predictions.png'></img>