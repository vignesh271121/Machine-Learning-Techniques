# Machine-Learning-Techniques
<h2>How to Install and Run</h2>

<b>STEP 1</b>: Make sure ANACONDA is installed on your workstation. If you dont have it, you can get it here ---> https://www.anaconda.com/products/distribution

<b>STEP 2</b>: Fork this repo. Start by making sure you're logged into GitHub. Then click the Fork button in the upper-right hand corner of this page (https://github.com/vignesh271121/Machine-Learning-Techniques) and follow the prompts.

<b>STEP 3</b>: Clone this repo. Click the green code button and copy the URL listed under 'HTTPS'. Now go to you IDE, such as VS Code, PyCharm or Atom, find a place to clone it and type 'git clone' plus the URL you just copied. For example 'git clone https://github.com/vignesh271121/Machine-Learning-Techniques.git'

<b>STEP 4</b>: Install opencv using anaconda prompt. Type pip install opencv-python

![image](https://user-images.githubusercontent.com/97229745/191010683-0406793a-6d21-4bc7-b114-9a69e2f0f1f5.png)

<b>STEP 5</b>: Check this url -https://cocodataset.org/#home. object detection for a pre-trained yolo model . next go to https://pjreddie.com/darknet/yolo/ and click on the configuration and weights and download both files.click on raw and then save as “yolo.cfg” remember to select all files to remove .txt extension. Save it inside model folder.

class_labels = ["person","bicycle","car","motorcycle","airplane","bus","train","truck","boat",
                "trafficlight","firehydrant","stopsign","parkingmeter","bench","bird","cat",
                "dog","horse","sheep","cow","elephant","bear","zebra","giraffe","backpack",
                "umbrella","handbag","tie","suitcase","frisbee","skis","snowboard","sportsball",
                "kite","baseballbat","baseballglove","skateboard","surfboard","tennisracket",
                "bottle","wineglass","cup","fork","knife","spoon","bowl","banana","apple",
                "sandwich","orange","broccoli","carrot","hotdog","pizza","donut","cake","chair",
                "sofa","pottedplant","bed","diningtable","toilet","tvmonitor","laptop","mouse",
                "remote","keyboard","cellphone","microwave","oven","toaster","sink","refrigerator",
                "book","clock","vase","scissors","teddybear","hairdrier","toothbrush"]


![image](https://user-images.githubusercontent.com/97229745/191009862-86cef685-cd49-47ef-9197-0012487e5f64.png)

<b>STEP 6</b>: Edit the download location. Create a folder named as images/testing and inside that folder put a file named scene2.jpg  

![image](https://user-images.githubusercontent.com/97229745/191010833-959bad6b-615d-483b-a297-4bc1e4b751bc.png)

<b>STEP 7</b>: Run the code pretrained_yolo_image.py. Open anaconda spider and create a new file were we are going to code the model.

![image](https://user-images.githubusercontent.com/97229745/191011482-06e6499d-3e80-4c97-ab2c-307bb82f0670.png)


