# holiday-chat
A Christmas-Themed Holiday Chat and Video Conferencing Platform to spend time and to form meaningful connections with strangers on holidays.

## Instructions:
* Run `pip install -r requirements.txt`.
* Download and unzip [ngrok](https://ngrok.com/download).
* Create a Twilio account. Create a new project and acquire your Twilio Credentials for the Video Conferencing.
* Create a text file named `.env` in the project directory with the following format:
    ```
    TWILIO_ACCOUNT_SID=<insert twilio account sid>
    TWILIO_API_KEY_SID=<insert api key sid>
    TWILIO_API_KEY_SECRET=<insert api key secret>
    ```
* Run `FLASK_ENV=development flask run` in the terminal in your project directory.
* While FLASK is running, on another terminal tab run `./ngrok http 5000` wherever the ngrok was unzipped.
* Give the `ngrok.io` temporary link to everyone who wants to meet up and use it. Enjoy.
