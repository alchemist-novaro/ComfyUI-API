# ComfyUI-API Integration Project
This is a project what I completed for a client.
The app is designed to process text to image or image to image tasks via comfyui-api, and upload processed image to firebase.
You can build comfyui integrated website or other apps referring to this app.
## Run project
- First, install dependencies.
```
pip install -r requirements.txt
```
- Second, you should export comfyui workflow as API format.
- Third, edit main.py file with your exact workflow path, prompt and other settings.
- Fourth, make `.env`file with your data.
```
PROJECT_ID=${your firebase project id}
FIREBASE_CERT_PATH=${your firebase certification path}
SERVER_URL=${your comfyui server url (e.g. localhost:8188)}
```
- Fifth, run main.py.
```
python -m main
```
