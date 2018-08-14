# partdetection

1. install darknet (guide: https://pjreddie.com/darknet/)
2. download the model file from google drive (https://drive.google.com/file/d/1tR8vvH5W02dKZq0lZeYUFxQdyhEEoRnI/view?usp=sharing)
3. detect the parts using:
   ./darknet detect yolov3_bird.cfg path_to_model.weights full_path_for_one_image.jpg [-thresh 0.2]
