## Running a python app on Google Cloud Platform - App Engine

1. Create a new project in [Google Cloud Platform](https://console.cloud.google.com)

2. Enable required [Google Cloud API's](https://console.developers.google.com/apis)

3. Download [Google Cloud SDK installer](https://dl.google.com/dl/cloudsdk/channels/rapid/GoogleCloudSDKInstaller.exe)

4. Launch the installer and follow the prompts

5. Once installed, setup the Google Cloud SDK using `gcloud init` and continue with configurations
```
gcloud init
```

6. Navigate to `testGCP/helloWorld` and use the following command:
```
gcloud deploy app.yaml
```
