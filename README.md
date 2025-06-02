# DIABETIC-RETINOPATHY-DETECTION-USING-DEEP-LEARNING
Diabetic Retinopathy is a disease with an increasing prevalence and the main cause of blindness among working-age population. The risk of severe vision loss can be significantly reduced by timely diagnosis and treatment. Systematic screening for DR has been identified as a cost-effective way to save health services resources. Automatic retinal image analysis is emerging as an important screening tool for early DR detection, which can reduce the workload associated to manual grading as well as save diagnosis costs and time. Many research efforts in the last years have been devoted to developing automated tools to help in the detection and evaluation of DR lesions. We are interested in automating this predition using deep learning models.

Dataset : APOTS Kaggle Blindness dataset

Dev Env.	             Framework/ library/ languages
Backend development  	 PyTorch (Deep learning framework)
Frontend development	 Tkinter (Python GUI toolkit)
Database connectivity	 HeidiSQL (MySQL server)
Programming Languages	 Python, SQL
API	                   Twilio cloud API




![mat](https://github.com/user-attachments/assets/0a010c4d-a848-48e0-902a-3ef3d216a99f)
![vis](https://github.com/user-attachments/assets/03af0651-4fc9-4bdd-9f17-5cc6c8bb65e5)
![image](https://github.com/user-attachments/assets/e97118f7-d822-400f-8133-5b74c1849a9d)
![image](https://github.com/user-attachments/assets/dd48c418-a29b-4785-a926-89b57ecafc86)



Installation :
Tip : Make sure to install Numpy, Pandas, Matplotlib first and then proceed next.

Torch package
Tkinter
HeidiSQL
Grab a cup of coffee as these will take some time !
click here to start server in HeidiSQL and configure settings by setting username and password.
Get, set and go :
Download complete Project files using following command from git bash/ cmd (terminal):
git clone https://github.com/souravs17031999/Retinal_blindness_detection_Pytorch   

[Note you need mainly these four things to get started :]

blindness.py model.py classifier.pt send_sms.py

Create a new database and table accordingly.
Then, Go to 'blindness.py' file and change some configuration settings according to your database.
connection = sk.connect(
    host="localhost",
    user="root",
    password="********",
    database="********"
)
Now, your DB server must be connected.
Finally, you also want 'classifier.pt' file which contains model's dictionary required when it is to be loaded.
Download here and put that file in the same directory and then modify the path accordingly in the 'model.py' file.
model = load_model('../Desktop/classifier.pt')

Finally, execute your 'blindness.py' file and your GUI must start (recommended to start this from your terminal and keep all your project files in same directory).
Upload the image and get your predictions.
credit:/souravs17031999
