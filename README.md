# My Portfolio website


<!-- TODO: Insert the link in between the parenthesis -->
👋  Hi! I'm Jeremy Nelson. I'm a recent Google Cloud Engineer Career Training Graduate from [Dallas, Texas](https://www.https://www.google.com/maps/place/Dallas,+TX/@32.8160108,-97.8135679,9z/data=!3m1!4b1!4m5!3m4!1s0x864c19f77b45974b:0xb9ec9ba4f647678f!8m2!3d32.7766642!4d-96.7969879?hl=en).  

This is the repository for [my portfolio](www.nelsonjjeremy.com). 

<br>

## The project
### Technologies used
I've used the following technologies:
- [Google App Engine](https://cloud.google.com/appengine/docs/overview)
- [Python](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)

## The app
The app is a simple website that I built to showcase my skills. It is a single page application that uses the [Flask](https://flask.palletsprojects.com/) framework. The app is deployed on Google App Engine. 

I've set some variables in `main.py` to make it easier to maintain the app. 

The variables are: 
- name
- role
- phone
- email
- location

## Folder structure
- Templated html files are located in `templates/`
- App engine configuration is located in `app.yaml` 
- The Flask code is located in `main.py`
- Images are located in `static/images/`
- My resume is located in `static/static/JeremyNelson_GeneralResume.pdf`

## Deployment
- To deploy this app **live**:
  - From a terminal, with Google Cloud SDK **OR** from the [Google's cloud shell](https://shell.cloud.google.com/):
      - `cd` into the `portfolio-template/` folder which contains the `app.yaml` config file (e.g.: `cd portfolio-template`)
      - Deploy the web app: `gcloud app deploy`

- To test this app **locally**:
  - From **[Google's cloud shell](https://shell.cloud.google.com/)**:
    - `cd` into the `portfolio-template/` folder which contains the `app.yaml` config file
      -   e.g.: `cd portfolio-template`
    - Run the following command to run the web server locally `dev_appserver.py app.yaml`
    - View the website by clicking on *preview on port 8080* (see image below) 
     ![image](https://user-images.githubusercontent.com/34327253/151443857-58edd60d-0731-4cc9-b963-48ba245fafde.png)


  - From your **local machine's terminal** (your computer), with Python installed:
    - Create a virtual environment:
      ```
      python3 -m venv env
      ```  
    - Activate the virtual environment:
        ```
        source env/bin/activate
        ```
    - Install dependencies:
        ```
        pip install -r requirements.txt
        ```
    - Run the app:
        ```
        python main.py
        ```
        The url for the app will be displayed in the terminal (e.g.  Running on http://127.0.0.1:5000/).
