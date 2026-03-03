#**🌾Farming**


#**Team Information**
 
 Hello,our team has five members are
    |** NAMES **| 
| ------ | 
|GUNTOJU VIJAYALAXMI|
| GATLA RAHUL     |
| JOGU YUGANDER   |
| MD.SONAM        |
|KOLLARA MAHESHWAR RAO|

  
We are from Pallavi Engeneering College


#**Application Overview** 
 
 Project title:Natural Farming
 Domain:Natural Agriculture
 
    
    🔍**Problem Being Solved**
    
     Now-a-days we are using pesticides and fretilizers for agriculture.Those are harmful to our health.
     So we need to Cultivate crops by using Natural fretilizer which are used in olden days.
     then we need to encourage peoples to Cultivate natural crops these will help for our health.

    
 #**MVP Scope**
     ✅we are creating a streamlit app and there is no required for login.
     ✅each data has its location,title and language.
     ✅all this are stored in database or any ofline files.

    **🌾Natural farming**
     ✅user can:
       submit text on Farming
       upload videos on Farming
       upload images on Farming
       upload audio-recording on Farming


**🛠️AI Integration Details**
 
 The core AI integration is designed to enhance data quality and usability while maintaining a lightweight, offline-first    approach suitable for low-bandwidth rural environments. The AI component serves primarily to assist users in generating richer, more structured content and to prepare the collected corpus for future AI model training.
    
    **#AI Components and Models**
     
     1.Text-Processing and language detection
     2.Basic NLP
     3.Metadata Enrichment(submit audio,videos,images and text)
     4.Future integration map


**#Technical Architecture & Development**
    
    #**1.Frontend: Streamlit Web Application**
     
     ✅Framework: Streamlit — chosen for rapid prototyping, ease of use, and seamless deployment.
     ✅UI Components:
       Input forms for text stories, image, audio, and video uploads.
       name, location, language.
       Buttons clearly separated for each media type with appropriate validation.
       Multilingual Support: Text inputs accept Unicode characters. 
       language selection enables future filtering and categorization.
    
    #**2. Backend: Data Handling & Storage**
    
     ✅File Storage
     ✅Data Storage
    
    #**3. Security & Data Integrity**
    
    #**4.Deployment & Hosting**
    
    #**5.Development Workflow**
     
     Day 1-2: Setup project structure, Streamlit interface, and file upload handlers.
     Day 3-4: Build SQLite database schema and implement backend save/load logic.
     Day 5: Integrate AI preprocessing for text and metadata enrichment.
     Day 6: Optimize for offline use and low bandwidth; implement UI improvements.
     Day 7: Testing and bug fixes, deploy MVP to Hugging Face Spaces.
     

**🎨Diagram**
     
     
    [User Browser] <---> [Streamlit Frontend]
        |                    |
        | Uploads/Text Input |
        |                    |
   [Local File Storage]  <---> [SQLite Database]
        |                    |
        | AI Processing       |
        | (Language Detection,|
        | Keyword Extraction) |


**#User Testing & Feedback**
    
    **📝Objective**
     
     The primary objective of Week 2 was to ensure that the MVP was accessible, functional, and intuitive for users 
     from rural and     semi-rural areas—especially those with low digital literacy and limited internet bandwidth. 
     We aimed to validate:

      Ease of content submission (text, image, audio, video)

      Language and location tagging

      Performance under low-connectivity conditions

      Usability across devices (mobile-first focus)
  
  **📝Testing Methodology**
    
    
    **#Devices Used:**
     
     10 Android smartphones (4G, limited data)

     3 entry-level laptops (shared)

     2 users with 2G/slow connections (to simulate offline-first performance)

  **#Tasks Given to Users:**

    **🌾Natural farming** 
     Submit a text story or memory related to natural farming.

     Upload a photo of a crop or farming tool.

     Record and upload a short audio (e.g., a farming tip).

     Try uploading a short video describing a traditional practice.

     Select their local language and location from the app.
z

    **#Observation Criteria:**
     
     Could users complete each submission independently?

     Did any input fields confuse them?

     Did files successfully upload under slow internet?

     Were they aware of what was being collected and why?

     Was the interface understandable without English fluency?

    **🧾Feedback Collection**
     
     Direct observation (via Zoom or in-person)
     
     WhatsApp voice notes and follow-up calls

     Google Form (translated into Telugu)

     On-screen satisfaction rating (1–5 stars) added temporarily