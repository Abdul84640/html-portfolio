<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e0e0e0; /* Background color */
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .resume {
            width: 80%;
            max-width: 800px;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .header {
            background-color: #007bff; /* Header background color */
            color: #ffffff; /* Header text color */
            display: flex;
            align-items: center;
            padding: 20px;
            border-bottom: 2px solid #333333;
            position: relative;
        }

        .header h1 {
            margin: 0;
            font-size: 32px;
            flex-grow: 1;
            color: #ffffff; /* Header title text color */
        }

        .header p {
            margin: 5px 0 0;
            font-size: 18px;
            color: #ffffff; /* Header subtitle text color */
        }

        .photo-box {
            width: 100px;
            height: 100px;
            background-color: #f4f4f4;
            border: 2px solid #ffffff;
            border-radius: 50%;
            overflow: hidden;
            position: absolute;
            top: 50%;
            right: 20px;
            transform: translateY(-50%);
        }

        .photo-box img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .contact-info {
            text-align: center;
            margin: 20px 0;
            font-size: 14px;
            color: #555555;
        }

        .section {
            margin-bottom: 20px;
        }

        .section h2 {
            margin-bottom: 10px;
            font-size: 22px;
            color: #007bff; /* Section header text color */
            border-bottom: 1px solid #000000;
            padding-bottom: 5px;
            text-align: left;
        }

        .job, .education {
            margin-bottom: 15px;
        }

        .job h3, .education h3 {
            margin: 0;
            font-size: 18px;
            color: #007bff; /* Job and education header text color */
            text-align: left;
        }

        .job p, .education p {
            margin: 5px 0;
            font-size: 14px;
            color: #666666;
            text-align: justify;
        }

        ul {
            padding-left: 20px;
            color: #666666;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
        }

        .skills li {
            list-style-type: none;
            background-color: #f0f0f0;
            padding: 5px;
            text-align: center;
            border-radius: 5px;
            color: #333333;
        }
    </style>
</head>
<body>
    <div class="resume">
        <div class="header">
            <h1>SHAIK ABDUL HAMEED</h1>
            
            <div class="photo-box">
                <img src="image1.png" alt="Your Photo">
            </div>
        </div>

        <div class="contact-info">
            <p>Email: hameedcrawlerstechnologies@gmail.com</p>
            <p>Phone: 8464081307</p>
            <p>Address: kadapa, Andhra Pradesh, INDIA</p>
        </div>

        <div class="section">
            <h2>Summary</h2>
            <p>I Am a Loyal and Trustworthy Employee Who Can Work Alone or as part of a Team. I am a Quick to Learn and Willing to Adapt to any Job. </p>
        </div>

        <div class="section">
            <h2>Work Experience</h2>
            <div class="job">
                <h3>FULL STACK DEVELOPER</h3>
                <p>I'M Currently Working As A Full Stack Developer At Crawlers Technologies Pvt Ltd</p>
               
            </div>
            
        </div>

        <div class="section">
            <h2>Education</h2>
            <div class="education">
                <UL>
                    <LI>I Have completed My B-tech in VITS with 70%</LI>
                    <li>I Have completed My Intermediate in Sri Daata Sai Junior College with 75%</li>
                    <li>I Have completed My SSC in Narayana School with 85%</li>
                </UL>
               
            </div>
        </div>

        <div class="section">
            <h2>Skills</h2>
            <ul class="skills">
                <li>HTML</li>
                <li>JAVA</li>
                <li>CSS</li>
                
            </ul>
        </div>
    </div>
</body>
</html>
