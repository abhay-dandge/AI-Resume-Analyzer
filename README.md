<p><small>Best View in <a href="https://github.com/settings/appearance">Light Mode</a> and Desktop Site (Recommended)</small></p><br/>

![AI-Resume-Analyzer]
<div align="center">
  <h1>🌴 AI RESUME ANALYZER 🌴</h1>
  <p>A Tool for Resume Analysis, Predictions and Recommendations</p>
  <!-- Badges -->

  


## About the Project 🥱

      A tool which parses information from a resume using natural language processing and finds the keywords, cluster them onto sectors based on their keywords. 
      And lastly show recommendations, predictions, analytics to the applicant / recruiter based on keyword matching.
    </p>
</div>

## Scope 😲
i. It can be used for getting all the resume data into a structured tabular format and csv as well, so that the organization can use those data for analytics purposes

ii. By providing recommendations, predictions and overall score user can improve their resume and can keep on testing it on our tool

iii. And it can increase more traffic to our tool because of user section

iv. It can be used by colleges to get insight of students and their resume before placements

v. Also, to get analytics for roles which users are mostly looking for

vi. To improve this tool by getting feedbacks

<!-- TechStack -->
## Tech Stack 🍻
<details>
  <summary>Frontend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/HTML">HTML</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS">CSS</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/JavaScript">JavaScript</a></li>
  </ul>
</details>

<details>
  <summary>Backend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li><a href="https://www.python.org/">Python</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.mysql.com/">MySQL</a></li>
  </ul>
</details>

<details>
<summary>Modules</summary>
  <ul>
    <li><a href="https://pandas.pydata.org/">pandas</a></li>
    <li><a href="https://github.com/OmkarPathak/pyresparser">pyresparser</a></li>
    <li><a href="https://pypi.org/project/pdfminer3/">pdfminer3</a></li>
    <li><a href="https://plotly.com/">Plotly</a></li>
    <li><a href="https://www.nltk.org/">NLTK</a></li>
  </ul>
</details>

<!-- Features -->
## Features 🤦‍♂️
### Client: -
- Fetching Location and Miscellaneous Data

  Using Parsing Techniques to fetch
- Basic Info
- Skills
- Keywords

Using logical programs, it will recommend
- Skills that can be added
- Predicted job role
- Course and certificates
- Resume tips and ideas
- Overall Score
- Interview & Resume tip videos

### Admin: -
- Get all applicant’s data into tabular format
- Download user’s data into csv file
- View all saved uploaded pdf in Uploaded Resume folder
- Get user feedback and ratings
  
  Pie Charts for: -
- Ratings
- Predicted field / roles
- Experience level
- Resume score
- User count
- City
- State
- Country

### Feedback: -
- Form filling
- Rating from 1 – 5
- Show overall ratings pie chart
- Past user comments history 

## Requirements 😅
### Have these things installed to make your process smooth 
1) Python (3.9.12) https://www.python.org/downloads/release/python-3912/
2) MySQL https://www.mysql.com/downloads/
3) Visual Studio Code **(Prefered Code Editor)** https://code.visualstudio.com/Download
4) Visual Studio build tools for C++ https://aka.ms/vs/17/release/vs_BuildTools.exe

## Setup & Installation 👀

To run this project, perform the following tasks 😨

Download the code file manually or via git
```bash
git clone 
```

Create a virtual environment and activate it **(recommended)**

Open your command prompt and change your project directory to ```AI-Resume-Analyzer``` and run the following command 
```bash
python -m venv venvapp

cd venvapp/Scripts

activate

```

Downloading packages from ```requirements.txt``` inside ``App`` folder
```bash
cd../..

cd App

pip install -r requirements.txt

python -m spacy download en_core_web_sm

```

After installation is finished create a Database ```cv```

And change user credentials inside ```App.py```


Go to ```venvapp\Lib\site-packages\pyresparser``` folder

And replace the ```resume_parser.py``` with ```resume_parser.py``` 

which was provided by me inside ```pyresparser``` folder

``Congratulations 🥳😱 your set-up 👆 and installation is finished 😵🤯``

I hope that your ``venvapp`` is activated and working directory is inside ``App``

Run the ```App.py``` file using
```bash
streamlit run App.py

```

## Known Error 🤪
If ``GeocoderUnavailable`` error comes up then just check your internet connection and network speed

## Issue While Installation and Set-up 🤧
Check-out installation [Video](https://youtu.be/WFruijLC1Nc)



## Usage
- After the setup it will do stuff's automatically
- You just need to upload a resume and see it's magic
- Try first with my resume uploaded in ``Uploaded_Resumes`` folder
- Admin userid is ``admin`` and password is ``admin@resume-analyzer``

<!-- Roadmap -->
## Roadmap 🛵
* [x] Predict user experience level.
* [x] Add resume scoring criteria for skills and projects.
* [x] Added fields and recommendations for web, android, ios, data science.
* [ ] Add more fields for other roles, and its recommendations respectively. 
* [x] Fetch more details from users resume.
* [ ] View individual user details.

## Contributing 🤘
Pull requests are welcome. 




## Preview 👽

### Client Side

**Main Screen**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/user/1-main-screen.png?raw=true)

**Resume Analysis**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/user/2-analysis.jpg?raw=true)

**Skill Recommendation**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/user/3-recom.png?raw=true)

**Course Recommendation**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/user/4-recom.png?raw=true)

**Tips and Overall Score**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/user/5-tipsscore.png?raw=true)

**Video Recommendation**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/user/6-recom.png?raw=true)

### Feedback

**Feedback Form**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/feedback/1-form.png?raw=true)

**Overall Rating Analysis and Comment History**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/feedback/2-analytics.png?raw=true)

### Admin

**Login**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/1-main-screen.png?raw=true)

**User Count and it's data**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/2-user-data.png?raw=true)

**Exported csv file**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/3-user-datacsv.png?raw=true)

**Feedback Data**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/4-feed-data.png?raw=true)

**Pie Chart Analytical Representation of clusters**

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/5-pieexp.png?raw=true)

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/6-piescre.jpg?raw=true)

![Screenshot](https://github.com/deepakpadhi986/AI-Resume-Analyzer/blob/main/screenshots/admin/7-pielocation.png?raw=true)


