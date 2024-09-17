# Let's create the HTML file and save it correctly for the user to download.
html_content = """
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="الصفحة الشخصية لعبد الملك عيد - خبير الأمن السيبراني">
    <title>عبد الملك عيد - خبير الأمن السيبراني</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        main {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background-color: white;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            color: #333;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #4CAF50;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>عبد الملك عيد</h1>
        <p>خبير الأمن السيبراني</p>
    </header>
    <main>
        <section>
            <h2>الملخص الشخصي</h2>
            <p>خبير أمن سيبراني يتمتع بخبرة تتجاوز 8 سنوات في تصميم وتنفيذ حلول حماية متقدمة للشركات والحكومات. شغوف بإيجاد حلول مبتكرة للتحديات السيبرانية الجديدة، ومتمرس في تحديد نقاط الضعف وتأمين الشبكات والبنى التحتية الحرجة.</p>
        </section>
        
        <section>
            <h2>الخبرات المهنية</h2>
            <h3>شركة XYZ للأمن السيبراني - مدير أمن المعلومات (CISO)</h3>
            <p>يناير 2021 - حتى الآن</p>
            <ul>
                <li>قيادة استراتيجية الأمن السيبراني الشاملة للشركة.</li>
                <li>تحقيق تقليل بنسبة 40% في تعرض الشركة للهجمات السيبرانية.</li>
            </ul>

            <h3>شركة ABC للتكنولوجيا - مهندس أمان سيبراني رئيسي</h3>
            <p>مارس 2016 - ديسمبر 2020</p>
            <ul>
                <li>تصميم وتنفيذ أنظمة الأمان المتكاملة للشركات الكبرى.</li>
                <li>تقليل الأخطاء البشرية بنسبة 25% من خلال التدريب على الأمن السيبراني.</li>
            </ul>
        </section>
        
        <section>
            <h2>المهارات التقنية</h2>
            <ul>
                <li>اللغات البرمجية: Python, Java, C++, PowerShell</li>
                <li>الأدوات: Wireshark, Metasploit, Burp Suite, Nessus, Splunk</li>
                <li>أمن الشبكات: VPN, Firewalls, IDS/IPS, Zero Trust</li>
            </ul>
        </section>

        <section>
            <h2>المشاريع الكبرى</h2>
            <ul>
                <li>مشروع مواجهة هجمات الفدية للمؤسسات الحكومية.</li>
                <li>نظام الكشف عن التهديدات السيبرانية باستخدام الذكاء الاصطناعي.</li>
            </ul>
        </section>

        <section>
            <h2>التعليم</h2>
            <p>بكالوريوس في هندسة الحاسوب والأمن السيبراني - جامعة التقنية الوطنية (2011 - 2015)</p>
        </section>

        <section>
            <h2>الجوائز والتكريمات</h2>
            <ul>
                <li>أفضل خبير أمن سيبراني لعام 2023</li>
                <li>جائزة الابتكار في الأمان الرقمي</li>
            </ul>
        </section>

        <section>
            <h2>روابط التواصل</h2>
            <p>البريد الإلكتروني: <a href="mailto:abdulmalikeed@gmail.com">abdulmalikeed@gmail.com</a></p>
            <p>LinkedIn: <a href="https://linkedin.com/in/abdulmalikeed" target="_blank">linkedin.com/in/abdulmalikeed</a></p>
            <p>GitHub: <a href="https://github.com/Abdulmalikeed" target="_blank">github.com/Abdulmalikeed</a></p>
            <p>تلجرام: <a href="https://t.me/Abdulmalikeed" target="_blank">https://t.me/Abdulmalikeed</a></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 عبد الملك عيد - جميع الحقوق محفوظة</p>
    </footer>
</body>
</html>
"""

# Save the HTML content to a file
file_path = '/mnt/data/abdul_malik_eid_profile.html'
with open(file_path, 'w') as file:
    file.write(html_content)

file_path
