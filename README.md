## 3.2. Deployment pipeline to a cloud service

Link to deployed application:
https://dwd1.onrender.com/

On a push to main that changes folder 1_13/ content, the Github Actions workflow (*.github/workflows/render-deploy.yaml*) is triggered which calls Render's deploy hook. Render then rebuilds the image and redeploys the service.