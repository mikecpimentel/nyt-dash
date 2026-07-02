# NYT Dash (2022)
Note: I did not upload the code to Github at the time. The repo is sitting in my old laptop, which I can resurrect on request.
<br><br>
<img width="1072" height="481" alt="Home page" src="https://github.com/user-attachments/assets/bd6c58bb-8cb9-49cc-8891-2138ca28dfbe" />
<br>
<br>
This app allowed users to explore nearly two centuries of New York Times journalism.
<br><br>
<img width="548" height="344" alt="Paper explorer" src="https://github.com/user-attachments/assets/831362a8-72b3-4f34-b23e-8ec15f0a91ac" />
<br><br>
As an avid reader of the New York Times since my early 20s, I thought this would be an interesting and quick project to work on. I sought to organize 172 years of New York Times article metadata and unearth some interesting stuff.
<br><br>
For this project, I needed to efficiently insert tens of millions of rows into a PostgreSQL database. Because of the large amount of data involved, I did my processing on AWS and discarded unused pieces of data. After building the database, I performed database indexing and optimizations to ensure all my SQL queries ran quickly.
<br><br>
This application consisted of a React frontend and a Node.js backend.
<br><br>
**Role:** Frontend Engineer, Backend Engineer, Data Engineer, Designer \
**Tools:** React, JavaScript, PostgreSQL, MUI, HTML, CSS, Node.js, AWS
