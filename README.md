# Animator

## Implementation for animator modules:
- Point to Note: <br> 
All these images generated by GAN have a common pattern. Every face's eyes lies in the same coordinates.
- Working of GANS: <br>
Generative as the name suggests tries to generate fake images that look like real images. It learns the features of X. The generator takes (random features) as input noise.<br>
The discriminator is a binary classifier and tries to discriminate the real images and the images created by the generator. It learns the probability of class Y (real or fake) given features X. The probabilities are the feedback for the generator.<br>

- In Short: <br>
Generator learns to make fakes that look real. Discriminator learns to distinguish real from fake.


## Steps in Training GAN's:
- Define Generator and Discriminator
- Train Generator to generate fake data for the discriminator
- Train Discriminator to differentiate real vs fake data
- Continue => Train => Save

## Flow of GAN:<br>  
Noise → Generator → Features → Discriminator → Output → Cost (output)<br>
<img src="https://github.com/reekithak/Animator-Modules/blob/main/images/GANFLow-1.JPG">

## DataSet:<br>
- Cartoon Set -> [Get it here](https://google.github.io/cartoonset/)
<img src="https://github.com/reekithak/Animator-Modules/blob/main/images/cartoonGan.JPG">

## User Interface
- Using Simple Html-Css UI.

### Input UI
<img src="https://github.com/reekithak/Animator/blob/main/templates/simpleui.JPG"> <br>

### Output UI
<img src="https://github.com/reekithak/Animator/blob/main/templates/outputUI.JPG">




## Run the Application in your own Device ?

### Step 1:
Install [Python 3.7](https://www.python.org/downloads/release/python-370/)  
Don't forget to add Path o Environment Varibales [Doubt?](https://www.educative.io/edpresso/how-to-add-python-to-path-variable-in-windows)

Completely Optional:
Install [Git](https://git-scm.com/downloads)

### Step 2:
Clone this Repository [Tutorial](https://www.youtube.com/watch?v=O72FWNeO-xY)

### Step 3:
From the root folder of the repository, open a commandline terminal/powershell and run the following commands:<br />


`pip install virtualenv` :- Installs Virtualenv Python Module<br />
`virtualenv ANY_NAME` :- Replace ANY_NAME with your choice of environment name<br />
`.\ANY_NAME\Scripts\activate` :- Activates the Virtual Environment we just created<br />
`pip install -r requirements.txt` :- Installs the Required Liraries , Takes time & Needs Space ("A lot")<br />


### Step 4:
Once all the Above is Completed , Lets run our Application.

simply type in `python app.py` into the console / terminal.
The application will be hosted into the local server.

### Step 5:
The Above steps makes it possible to run the Complete Application


## Need the Complete Application along with the Models? 
Reach out to us :). <br>
[Akhil Sanker](https://www.linkedin.com/in/akhilsanker/)

- NOTE: Open Source Code Used

