# Real-Time Object Detection Using Yolov2 and Distance Estimation

This project repository provides a means that can be used to find the distance of an object or an indication of how close the object is, to the camera lens.
The codes present in this perfume are simply attempts to scan deep concepts for calculating the distance of objects from camera lenses.

## Real-Time Object Detection and Distance Estimation GUI

<table>
  <tbody>
	<tr align="center"> 
		<th><strong>Object Detection Distance Estimation Bench 1</strong></th>
	</tr>
	<tr align="center">
		<td><img src="results/bench_results1.jpg"></td>		
	</tr>
	<tr align="center"> 
		<th><strong>Object Detection Distance Estimation Bench 2</strong></th>
	</tr>
	<tr align="center">
		<td><img src="results/bench_results2.jpg"></td>		
	</tr>
	<tr align="center"> 
		<th><strong>Object Detection Distance Estimation Bench 3</strong></th>
	</tr>
	<tr align="center">
		<td><img src="results/bench_results3.jpg"></td>		
	</tr>
	<tr align="center"> 
		<th><strong>Object Detection Distance Estimation Bench 4</strong></th>
	</tr>
	<tr align="center">
		<td><img src="results/bench_results4.jpg"></td>		
	</tr>
</tbody>
</table>

## YOLOv2

You only look once (YOLO) is an object detection system targeted for real-time processing. We will introduce YOLO, YOLOv2 and YOLO9000 in this article. For those only interested in YOLOv3, please forward to the bottom of the article. Here is the accuracy and speed comparison provided by the YOLO web site.

## Requirement
<ul>
<li>OpenCV 4.2.0</li>
<li>Python 3.7</li>
</ul>

## Quick start
<ul>
  <li>Download official <a href="https://pjreddie.com/media/files/yolov2.weights" rel="nofollow">yolov3.weights</a> and place it under a folder called weight.</li>  
  <li>Download <a href="https://github.com/pjreddie/darknet/blob/master/cfg/yolov2.cfg">yolov2.cfg</a> and place it under a folder called cfg.</li>
</ul>

## Dependencies
<ul>
<li>opencv</li>
<li>numpy</li>
</ul>

## Install dependencies
<p><code>pip install numpy opencv-python</code></p>

## How to use?
<ol>
  <li>Clone the repository</li>
  <p><code>git clone https://github.com/muhammadshiraz/Real-time-object-detection-using-yolov2-and-distance-estimation.git</code></p>
</ol>
<ol start="2">
  <li>Move to the directory</li>
  <p><code>cd Real-time-object-detection-using-yolov2-and-distance-estimation</code></p>
</ol>
<ol start="3">
  <li>To view the object detection distance estimation bench 1</li>
  <p><code>python Object_Detection_Distance_Estimation_Bench_1.py</code></p>
</ol>
<ol start="4">
  <li>To view the object detection distance estimation bench 2</li>
  <p><code>python Object_Detection_Distance_Estimation_Bench_2.py</code></p>
</ol>
<ol start="5">
  <li>To view the object detection distance estimation bench 3</li>
  <p><code>python Object_Detection_Distance_Estimation_Bench_3.py</code></p>
</ol>
<ol start="6">
  <li>To view the object detection distance estimation bench 4</li>
  <p><code>python Object_Detection_Distance_Estimation_Bench_4.py</code></p>
</ol>

## Run by PyCharm IDE:
 
#### Object Detection Distance Estimation
<img src="results/RunbyPyCharmIDE.jpg">
