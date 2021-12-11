### Computer vision pipeline (semantic segmentation and object detection)

This computer vision pipeline mainly focused on segmenting image and detect objects in this image sequentially. Therefore, it could be applied into those scenarios with segmentation and object detection tasks, like self-driving, medical diagnosis.

The code part aims at providing a lightweight framework to compile this two tasks in the same project. The first file is about training the FCN-32s model weights on COCO dataset. In ths second part of code file, it compiled the already trained FCN model and YOLO model together to do prediction on arbitary input image, so the prediction outcome will be visualized with the image segmented with patches in different colors and objects in the image rounded with bounding box and labels indicating its class.
