#People Counting

Just plug and play with this software. It can calculate number number of people comming to the shop and going out from the shop. 

Thanks...

USAGE
To read and write back out to video:
python people_counter.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt  --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel --input videos/example_01.mp4 
 --output output/output_01.avi


To read from webcam and write back out to disk:
python people_counter.py --prototxt mobilenet_ssd/MobileNetSSD_deploy.prototxt --model mobilenet_ssd/MobileNetSSD_deploy.caffemodel 
--output output/webcam_output.avi
