# Please Support This Project!

I would appreciate a donation if you found it useful.

[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=53CD2WNX3698E&lc=US&item_name=PREngineer&item_number=K3S%2dDeployments&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)

You can also support me by sending a BitCoin donation to the following address:

19JXFGfRUV4NedS5tBGfJhkfRrN2EQtxVo

# K3S Deployments
A list of Light Kubernetes deployment manifest files to run applications in a cluster made up of Raspberry Pis.

# About

This list is by no means comprehensive of all the things that you can successfully run in Kubernetes in Raspberry Pis.

It will cover, however, all the deployments that I showcase in my YouTube channel's videos regarding this topic.

As of now, it includes:

  1. Jenkins CI/CD
  2. ...

# How to Use

  * Step 1 - Find the deployment manifest of interest within the repository

  * Step 2 - Copy its RAW content URL.  You can do so by navigating in your browser to the repository, clicking on the deployment file, then clicking the RAW button on the top right.  Copy the URL that starts with : https://raw.githubusercontent.com/Tech-Byte-Tips/

  * Step 3 - Grab the file from your K3S cluster's master raspberry pi by running wget.  Example:

  ```
  wget https://raw.githubusercontent.com/Tech-Byte-Tips/K3S-Deployments/DevOps-Tools/jenkins-deployment.yaml
  ```

  * Step 4 - Run the deployment

  ```
  kubectl apply -f <application>-deployment.yaml
  ```

# License

All rights are reserved by Jorge Pabón.

Free to use for personal use.
Use of this application for commercial purposes without a license is not authorized.
For licensing costs contact Jorge Pabón at pianistapr@hotmail.com.
