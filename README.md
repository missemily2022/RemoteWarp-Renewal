<p align="center">
    <a href="https://github.com/missemily2022/RemoteWarp-Renewal">
        <img width="200" src="https://1.1.1.1/media/warp-desktop.png" alt="RemoteWarp-Renewal">
    </a>
</p>


<p align="center">

## UnlimitedWrapUsage - RemoteServer

<p> A simple python script which can be run on remote servers for getting unlimited quota renewal on Cloudflare WARP+ 

</p>

### Q. How to get the WARP+ ID? 

<b>NOTE :</b> Run these steps in Android or iOS App.You cannot do this in PC <br>

Go to *Settings > Advanced > Diagnostics* and copy the **ID** under *CLIENT CONFIGURATION* section

### Q. Why the WARP+ quota is still showing 0 GB?

<b>NOTE :</b> Run these steps in Android or iOS App.You cannot do this in PC <br>

Go to *Settings > Advanced > Connection options* and press on **Reset security keys**

### Q. How to use the Wrap + Data that we get in License Key in PC ?

Go to *Settings > Account > Key* and copy the License Key <br>
Now paste this License Key ina a PC and get the Wrap+ Quota on your PC too.<br>

<b>Important : </b>You can fill your Cloudflare Warp+ ID in config.env and deploy the App. 

## ☂ Deploying on Railway.app

1. For Direct Deploy,Click on the Below Button<br/>
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Fmissemily2022%2FRemoteWarp-Renewal&envs=warp_id&warp_idDesc=Your+Cloudflare+Warp+Plus+ID&referralCode=jimmy)

2. Fill the following Environment Values as per below Instructions: 

> warp_id = Your Cloudflare Warp Plus ID
>

3. Click on Deploy
4. Wait a little bit.You will see that your app has been deployed to Railway and then you can clone without any Time Limit.<b>Railway does not restart App every 24 hours meaning your task can run for days at a time </b><br/><br/>

## ⚛️ Deploying on Heroku
 
1. Click on the button below :
<p><a href="https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2F&template=https://github.com/missemily2022/RemoteWarp-Renewal"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" alt="Deploy to Heroku" /></a></p>

2. Fill the following value : 

> warp_id = Your Cloudflare Warp Plus ID
>

3. Click on Deploy app...
4. When it's over, go to : https://dashboard.heroku.com/apps/YOURAPPNAME/resources (replace YOURAPPNAME by your appname 🙃)
5. Then click on the ✏ and check $0.00 option and click on confirm.
6. Now you can start your bot !
<br/><br/>