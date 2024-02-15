# LS401_Threejs_WebGL_Programming
Program webgl using Three.js library. Hosting the webpage on the Python Flask server.

In this task, you will be asked to draw a 3D graphics scene using Three.js, a WebGL based graphics library for 3D content rendering on webpage. To host the webpage, you are going to use a Python web server framework named Flask to set up your server. We have the starter code for you!

# If you are doing zoom interview, start from Step 1. If you are doing in-person interview, start from Step 3.

## Step 1: Clone the github repo

## Step 2: Configure Python development environment

To create a conda environment, typing:
```
conda create -n LS401 python=3.8
```
A conda environment LS401 with python 3.8 will be created. After creating this conda environment, activate it by typing:


```
conda activate LS401
```
Install the Flask and Flask_Cors packages we are going to use by
```
pip install Flask
pip install Flask-Cors
```
## Step 3: Run the server in starter code

The server code is already written for you in the starter code. Run the Flask server by executing the main.py file under 'server/' directory:

```
python server/main.py
```

It will return you the following information:

```
 * Serving Flask app 'main'
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on all addresses (0.0.0.0)
 * Running on http://127.0.0.1:8000
 * Running on http://xx.xx.xx.xx:8000
```
You can verify whether your server is up by opening the links above in the browser:

```
http://127.0.0.1:8000
```
It should return you 'Hello World!'.


## Step 4: Test the three.js code
We have copied an example code from into the /static/main.js file. You should see a rotating green cube after you visit:

```
http://127.0.0.1:8000/index.html
```
## Step 5: Create your virtual 3D scene!

Further modify the /static/main.js file, create your first 3D virtual scene. Your scene should try to contain the following elements:
<You can remove 
1. A ground plane.
2. One ball locate at the original point.
3. Two point light sources which create shadow effect on object.
   (optional) Visualize the light with point light helper.
4. (optional) Fly the camera by keyboard control and change the look at point by dragging the mouse.

