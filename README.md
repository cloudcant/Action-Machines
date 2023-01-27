# Action-Machines

_SSH into diffrent machines running in GitHub Actions_

_Relies on P3TERX/ssh2actions@main, go check out their page_

![image](https://user-images.githubusercontent.com/66269103/215143946-ed720da0-7d35-4a61-b901-27a152360ba7.png)


## _Preparation_

1. Fork This Repo
2. For ngrok Machines, Add your ngrok authtoken as `NGROK_TOKEN` in the Repository Secrets
   > You can find this token here: https://dashboard.ngrok.com/auth/your-authtoken
3. Add a shell login password as `SSH_PASSWORD` in the Repository Secrets
4. Go to Actions tab, select the workflow name you want, and run it through `workflow_dispatch` method
5. To connect , either connect with ssh through ngrok (if you choose ngrok), ssh through tmate , or through the tmate webshell. The connection info will show in the logs.

## _ScreenShots_

![image](https://user-images.githubusercontent.com/66269103/215141580-513aec49-8335-4eb7-a6c5-64ac37d55ec2.png)

![image](https://user-images.githubusercontent.com/66269103/215145486-16e846ae-333d-4d3a-907f-0cf971d98744.png)

