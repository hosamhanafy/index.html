# index.html
Hosam Mohamed CV
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My CV</title>
    <style>
        /* تصميم الصفحة */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }

        /* تصميم الرأس */
        header {
            position: relative;
            height: 300px;
            background-image: url('header-image.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
        }

        header .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
        }

        header h1 {
            margin: 0;
            padding-top: 100px;
            font-size: 2.5rem;
            z-index: 1;
            position: relative;
        }

        header p {
            margin: 0;
            font-size: 1.2rem;
            position: relative;
            z-index: 1;
        }

        /* تصميم الأقسام */
        section {
            padding: 20px;
            max-width: 900px;
            margin: 20px auto;
            background: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        section h2 {
            color: #333;
            margin-bottom: 10px;
        }

        section ul {
            padding: 0;
            list-style: none;
        }

        section ul li {
            margin-bottom: 10px;
        }

        /* فوتر */
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #0073e6;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <!-- قسم الهيدر -->
    <header>
        <div class="overlay"></div>
        <h1>Hossam Mohamed Hanafy</h1>
        <p>Sales Representative | GSK Consumer</p>
    </header>

    <!-- قسم المحتوى -->
    <section>
        <h2>About Me</h2>
        <p>Experienced Medical Sales Representative with over 10 years of experience in Kuwait’s pharmaceutical market, specializing in driving sales growth and building strong pharmacy relationships.</p>
        
        <h2>Experience</h2>
        <ul>
            <li><strong>Medical Sales Representative</strong> - CuraHealth (2015–Present)</li>
            <li><strong>Sales Associate</strong> - Previous Company (2010–2015)</li>
        </ul>
        
        <h2>Skills</h2>
        <ul>
            <li>Sales Strategy Development</li>
            <li>Pharmaceutical Sales</li>
            <li>Customer Relationship Management (CRM)</li>
        </ul>
    </section>

    <!-- فوتر -->
    <footer>
        &copy; 2024 Hossam Mohamed Hanafy. All Rights Reserved.
    </footer>
</body>
</html>
