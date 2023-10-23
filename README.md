
<html>
<head>
    <title>Resume - Trevor Milan</title>
    <meta charset="utf-8" />
    <meta http-equiv="Content-type" content="text/html; charset=utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="shortcut icon" type="image/png" href="/favicon.png"/>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
	<link rel="stylesheet" type="text/css" href="resume.css" media="screen" />
    <style type="text/css">
    body {
        background-color: #000000;
        margin: 0;
        padding: 0;
        font-family: "Lucida Console", Monaco, monospace;
        color: #CCC5B9;
    }
    </style>    
</head>

<body>
    <div>
        <div>
            <hr style="border-color:white; border-width:5px" />
            <center><strong>Welcome to my Terminal</strong></center>
            <center>Trevor Milan - <a href="https://github.com/kraten/terminal-resume" target="_blank">https://github.com/treevorxd</a></center>
            <hr style="border-color:white; border-width:5px" />
            </p>
        </div>

        <div id="resume-container">
            <div id="executed_commands">
                <div>Note: Enter <i>help</i> to get list of all available commands</div>
            </div>

            <div id="command-line">
                <span>&gt;&gt;</span>
                <input type="text" autofocus="autofocus" id="command" />
            </div>
        </div>
    </div>
    
    <!-- Resume Sections -->
    
    <!-- 1. About -->
    <div id="about">
        <div><strong>About Me</strong></div>
        <div>input text here</div>
        <div>
            <ul>
                <li><strong><a href="https://www.hackerearth.com/challenges/college/code-emblaze/" target="_blank">Code Emblaze</a> (2016)</strong>
                - Problem setter and organizer of a national-level coding competition on online coding platform HackerEarth, in which more 
                than 300 coders actively participated.</li>
                <li><strong>Rajasthan IT Day (2017) </strong>
                - Second Position in Blind Coding Event</li>
            </ul>
        </div>
    </div>
    
    <!-- 2. Education  -->
    <div id="education">
        <div><strong>Education</strong></div>
        <div>
            <ul>
                <li><strong>SKIT Jaipur, 2015-2019</strong></li>
                <p style="margin: 0">B.Tech Computer Science and Engineering</p>
                
                <li><strong>Step by Step High School Jaipur, 2012-2014</strong></li>
                <p style="margin: 0">Class 12th - 83.4%</p>
                
                <li><strong>St. Anselm’s North City School, Jaipur, 2005-2012</strong></li>
                <p style="margin: 0">Class 10th - 9.4 CGPA</p>
            </ul>
        </div>
    </div>

    <!-- 3. Projects  -->
    <div id="projects">
        <div><strong>Projects</strong></div>
        <div>
            <ul>
                <li><strong><a href="https://github.com/kraten/4K-Cloud" target="_blank">4K Cloud</a></strong> 
                - Developed a cloud platform to provide cloud services such as SaaS, PaaS, CaaS and STaaS and to automate the setup of 
                Hadoop Cluster and MapReduce Cluster using Ansible. Additional features include Face Recognition (Using pre-trained CNN), 
                Speech Synthesis and Recognition(Using JS libraries Annyang and SpeechKITT)</li>
                
                <li><strong><a href="https://github.com/kraten/vehicle-speed-check" target="_blank"> Vehicle Speed Check</a></strong> 
                - Predicts the speed of the vehicle from live video feed using computer vision. Built using Python, OpenCV and dlib</li>
                
                <li><strong><a href="https://github.com/kraten/chessbot" target="_blank">ChessBot</a></strong> 
                - Developed a bot that plays chess online on chess.com. Reached an ELO rating of 2600 (GrandMaster). Built using Python 
                Selenium to fetch the moves from website and play the best moves based on the prediction of Stockﬁsh Chess Engine.</li>  
                
                <li><strong><a href="https://djangopy.org" target="_blank">DjangoPy</a></strong> 
                - djangopy.org is a blog for Django enthusiasts. Built using Jekyll and hosted on GitHub.</li>
            </ul>
        </div>
    </div>

    <!-- 4. Experience  -->
    <div id="experience">
        <div><strong>Experience</strong></div>
        <div>
            <ul>
                <li><strong>Linux World Jaipur — Intern</strong></li>
                <p>Worked on developing a product, First Legal Aid. Users can ask any legal query and it will report back whether any 
                previous cases have been reported, which have a similar context and inform about diﬀerent actions he should take.</p>
            </ul>
        </div>
    </div>

    <!-- 5. Skills  -->
    <div id="skills">
        <div><strong>Technical Skills</strong></div>
        <div>
            <ul>
                <li><strong>Languages</strong> - C, C++, Python, Bash</li>
                <li><strong>Web Development</strong> - HTML, CSS, JavaScript</li>
                <li><strong>Operating Systems</strong> - Linux Distros(RHEL, Debian, Arch), Windows</li>
                <li><strong>Tools/Technologies</strong> - Docker, Ansible, OpenShift, Git</li>
            </ul>
        </div>

        <div><strong>Certifications</strong></div>
        <div>
            <ul>
                <li><strong>2018 Red Hat Certiﬁed System Administrator</strong></li>
                <li><strong>2015 NIIT Programming using C and C++</strong></li>                    
            </ul>
        </div>
    </div>

    <!-- 6. Contact  -->
    <div id="contact">
        <p>
            Email: <a href="mailto:bansal.kartike@gmail.com" target="_blank">bansal.kartike@gmail.com</a><br>
            LinkedIn: <a href="https://www.linkedin.com/in/kraten/" target="_blank">https://www.linkedin.com/in/kraten/</a><br>
            Github: <a href="https://github.com/kraten" target="_blank">https://github.com/kraten</a>
        </p>
    </div>

    <!-- 7. Download -->
    <div id="download">
        <p>Downloading resume..<br> 
        Note: If you are facing any problem, then click <strong><a href="./resume.pdf">HERE</a></strong> to download</p>
    </div>

    <!-- 8. Error -->
    <div id="error">
        <p><strong>Error</strong>: Command not found! Enter <i>help</i> to get list of all available commands..</p>
    </div>

    <!-- 9. clear -->
    <div id="clear"></div>

    <!-- 10. Help -->
    <div id="help">
        <div>
            ------------------  <br>
            Built-in Commands   <br>
            ------------------  <br>
            <p>about, education, projects, experience, skills, 
            contact, download, clear</p>
        </div>
    </div>
    <!-- Resume sections end -->

    <script type='text/javascript' src="resume.js"></script>    
</body>

</html>
