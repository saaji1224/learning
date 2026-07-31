# learning
# Installation steps for jenkins
  * run `jenskins.sh` file
  * if we want to change time zone for jekins
    ```bash
    timedatectl set-timezone Asia/Kolkata
    ```
  * Jenkins default path
    ```bash
    /var/lib/jenkins/
    ```
  * `Webhook` configuration - 
     ```bash
    repo settings --> webhook --> payload URL : http://15.207.110.158:8080/github-webhook/
    ```
  * Build Option 
    * `Build periodically` - Particular time it will be trigger using cron job expression. 
    * `Poll SCM` - It is depend on Git . It will trigger when developers commit the changes 

