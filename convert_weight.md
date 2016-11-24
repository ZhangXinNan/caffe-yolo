

```
python create_yolo_caffemodel.py \
    -m prototxt/yolo_train_val.prototxt \
    -w yolo.weights \
    -o yolo.caffemodel


python create_yolo_caffemodel.py \
    -m prototxt/yolo_tiny_train_val.prototxt \
    -w tiny-yolo.weights \
    -o tiny-yolo.caffemodel


python create_yolo_caffemodel.py \
    -m prototxt/yolo_small_train_val.prototxt \
    -w small-yolo.weights \
    -o small-yolo.caffemodel
```