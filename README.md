This is class task 5 attempted by the group The Plagiarizers.

### Members:

Muhammad Rohaan Atique - 20I-0410 (Member 2) <br>
Ahmed Moiz - 20I-2603 (Member 1) <br>
Zubair Fawad - 20I-1755 (Member 3) <br>

### Instructions to build and run the web service:

1. Download the image from dockerhub:<br>
  `docker pull theplagiarizers/ca5-web:35` <br>
  `docker pull theplagiarizers/ca5-db:2`
2. Run the docker image
   `docker-compose up`
3. Visit the main page of the website after image is running
   `http://localhost:8080` <br>
   
## Additional Details about our Implementation
#### In addition to the polling method, we also connected our github to our jenkins server using GitHub Hooks. <br>
<img width="1280" alt="image" src="https://github.com/theplagiarizers/CA5/assets/75722072/d8d2690e-c989-4000-8c40-a93ecc0273e9"> <br>
#### We used the multi-branch feature on Jenkins. This is how the dashboard looked like <br>
<img width="927" alt="image" src="https://github.com/theplagiarizers/CA5/assets/75722072/85282d69-38fd-4de6-a32b-314500bda33b"> <br>
#### We used a 5-stage deployment pipeline
<img width="900" alt="image" src="https://github.com/theplagiarizers/CA5/assets/75722072/732bfc85-a6cc-4ff5-b62e-94c9728897bf">
