# ML-Hindi-Video-Transciber
A short project I made in about 3 hours which uses Google API to take a hindi video, transcribe it in Hindi and then tell the subject matter being talked about as well

#TO RUN THE CODE

1.Have Jupyter notebooks software installed to run the .ipynb files

2. Go to google cloud API, create a google API key and enable the following APIs
Cloud Translation API	
Media Translation API	
Cloud Natural Language API
Cloud Speech-to-Text API

3. Replace the "creds.json" with your google API key json file
  Set Google Cloud credentials
os.environ['GOOGLE_APPLICATION_CREDENTIALS'] = 'creds.json'

4. For the first code, have the video file in the same folder.
    For the second code, have the input.txt in the same folder
