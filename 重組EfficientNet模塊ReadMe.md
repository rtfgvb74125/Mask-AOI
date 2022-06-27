# 重組EfficientNet模塊ReadMe
## EfficientNet_Block.py
此檔內是EfficientNet的Sub_Block模塊，可能自己需求調整個模塊中的神經層參數。

## Creat_Evolved_Model.py
此檔案中負責進行將Sub_Block模塊進行組合，並且可自行調整每個Sub_Block的Filter數量，詳細可參考Reorganized_Block4.py、Reorganized_Block5.py、Reorganized_Block6.py檔案。

## Reorganized EfficientNet.ipyd
可用此檔案訓練以及測試模型，當中的圖片處理方式可依照自己需求更改，或是使用image_generator方式取代。