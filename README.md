# Part detection model (yolo v3) for CUB200-2011 bird dataset

We provide the trained model (yolo v3) for detecting the parts of birds. Thought the model is trained on CUB200-2011 bird dataset, you can use it to detect any birds. If you are interested, please refer to work:

@article{
   author = {Feng, Hui and Wang, Shanshan and Ge, Shuzhi Sam},
   title = {Fine-grained visual recognition with salient feature detection},
   journal = {arXiv:1808.03935},
   year = {2018},
   type = {Journal Article}
}

--------------------------------------------------------------------------------------------------------------------------------
1. install darknet (guide: https://pjreddie.com/darknet/)
2. download the model file from google drive (https://drive.google.com/file/d/1tR8vvH5W02dKZq0lZeYUFxQdyhEEoRnI/view?usp=sharing)
3. detect the parts using:
   ./darknet detect yolov3_bird.cfg path_to_model.weights full_path_for_one_image.jpg [-thresh 0.2]

--------------------------------------------------------------------------------------------------------------------------------
