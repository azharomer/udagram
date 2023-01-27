### Pipeline

 application used circleCI to build and deploy on aws cloud .

 1- Github  
  ` after push && commit changes on the code 
   to githup repository . the CircleCI trigger to run config in folder .circleci/config.yml in root folder in app` 

  2- CircleCI 
  ` run when code changed in git project linked with CircleCI app .
  udagram app separeted to two frontend and backend api `.
 - udagram-frontend : run build and deploy to aws s3.
 -  udagram-api : run build and deploy to aws EB.