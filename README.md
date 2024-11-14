# Webapp_serverless- React+Type script
Learn to create a web app using AWS severless services</br>
Link: https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-amplify-bedrock-cognito-gen-ai/
## Architecture review
![image](https://github.com/user-attachments/assets/4a0fd78c-6913-4396-9246-9ab4631476ed)

## Steps
1) Configure AWS for local development</br>
Link: https://docs.amplify.aws/react/start/account-setup/
2) Host Static Website</br>
Link: https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-amplify-bedrock-cognito-gen-ai/module-one/

## Errors
### 1) Problem: npx : File C:\Program Files\nodejs\npx.ps1 cannot be loaded because running scripts is disabled on this system.</br>
Remediation: Run code "Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser" </br>

### 2) Problem: error: failed to push some refs to 'git@github.com/Joshleee7/profilesapp.git' </br>
![image](https://github.com/user-attachments/assets/b971ba79-0ff2-43c2-9ea0-055195bcbd97) </br>
Remediation: Generate public key with SSH and copy the key over to github SSH and GPG keys </br>
![image](https://github.com/user-attachments/assets/f82ba403-669d-4159-a62d-a1aab68cb11b)</br>

### 3) Problem: npx ampx sandbox error, credential issue </br> 
![image](https://github.com/user-attachments/assets/84344c8e-b531-4f5e-9c73-df855fd75af8)</br>
Remediation: provide access key and secret access key</br>
![image](https://github.com/user-attachments/assets/71098852-75ed-4ee0-ad39-b36ba7604a31) </br>
Steps to get access keys</br>
![image](https://github.com/user-attachments/assets/63e26ee5-45f7-456f-9702-ef0371aaa642)

### 4) Problem: Initial setup error, I created vue instead of react application in the beginning </br>
![image](https://github.com/user-attachments/assets/b0323135-0a9d-418c-97ed-09ff747b84b5)</br>
![image](https://github.com/user-attachments/assets/2537051b-d11d-4838-88dd-ad9e3b2362a3) </br>
![image](https://github.com/user-attachments/assets/894df274-6474-4273-aeb6-18757901ba35) </br>
Remediation: To reinstall the applcation with React+Javascript

### 5) Problem: Origin name differs</br>
![image](https://github.com/user-attachments/assets/bdf8d5ff-4f5d-404d-9d13-66df0042255c) </br>
Remediation: Remove the origin and add again </br>
![image](https://github.com/user-attachments/assets/88778408-1a62-4fec-8b45-3759e6541003)

## 6) Problem Security Token included in the request is expired in AWS </br>
![image](https://github.com/user-attachments/assets/77529111-7c49-4769-a8c1-1a7d1571dbf5)







