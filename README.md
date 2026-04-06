# LeetMetric – LeetCode Progress Tracker
LeetMetric is a web-based application that visualizes a user's LeetCode stats using a clean UI and animated progress circles. Built using HTML, CSS, and JavaScript, it fetches live data from the LeetCode GraphQL API and displays progress for Easy, Medium, and Hard problems along with submission counts.

#  Features
1.  Username Input with Validation
    -->  Accepts and validates LeetCode usernames before fetching data.
2.  Progress Circles
    --> Visual representation of solved vs total problems in Easy, Medium, and Hard categories using conic-gradient.
3.  Stat Cards
    --> Displays total number of submissions categorized by difficulty.
4.  Error Handling
    --> Displays alerts for invalid usernames or API failures.
5.  Live API Integration
    --> Fetches real-time data using LeetCode’s GraphQL API (via CORS proxy).

#  Technologies Used
HTML5 – Structure and layout
CSS3 – Styling and responsive design
JavaScript (Vanilla) – Logic, API calls, DOM manipulation
GraphQL API – Data from LeetCode
CORS Proxy – To bypass LeetCode's same-origin policy

# 📁 File Structure

    LeetMetric/
    ├── index.html        # Main HTML structure
    ├── style.css         # All styling (including animated progress circles)
    ├── script.js         # JavaScript logic and GraphQL API handling

#  Cloning a GitHub Repository
METHOD 1 -->
 Navigate to your project folder

         cd path/to/your/LeetMetric
Initialize Git (if not done) :

    git init
Add & commit your files :

    git add .
    git commit -m "Initial commit"
Link your repo :

    git remote add origin https://github.com/YOUR_USERNAME/LeetMetric.git
Push :

    git push -u origin main
    
METHOD 2  -->
If your repo is now online (e.g., https://github.com/SHIVANSHIDWIVEDI/LeetMetric), then to clone :

From terminal :
              git clone https://github.com/SHIVANSHIDWIVEDI/LeetMetric.git
 Result :
It will create a folder LeetMetric with all files (index.html, style.css, script.js) locally.

# Screenshot
<img width="845" height="531" alt="Screenshot 2025-07-22 192858" src="https://github.com/user-attachments/assets/9abc40b6-18c2-4cd7-a635-900525a39fa7" />

