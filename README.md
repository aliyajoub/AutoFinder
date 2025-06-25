 # AutoFinder
## Application Description

AutoFinder is an integrated application for extracting and processing car listings from various social media platforms such as Facebook and TikTok. The application uses artificial intelligence and computer vision technologies to identify cars in images and videos, and extract important information such as model, manufacturer, year, price, location, plate number, color, and chassis numbers.

The application provides an API that allows users to search for specific cars using plate numbers or chassis numbers, helping to facilitate the process of buying and selling used cars and providing accurate and reliable information.

### How the Application Works

The application works through the following steps:

1. **Data Extraction**: The application visits car pages and groups on social media platforms and extracts posts containing car information.

2. **Text Processing**: The application uses natural language processing techniques to extract important information from post texts such as model, year, price, and more.

3. **Image Analysis**: The application uses the YOLO model to detect cars in images, then uses computer vision techniques to analyze the car's color and characteristics.

4. **Text Extraction from Images**: The application uses OCR (Optical Character Recognition) technology to extract text from images, such as license plate numbers.

5. **Video Processing**: The application extracts frames from videos and processes them in the same way as images.

6. **Data Storage**: All extracted information is stored in a Supabase database.

7. **API Interface**: The application provides an API interface that allows users to search for cars and access information.

### Technologies Used

- **FastAPI**: A framework for building API interfaces with Python.
- **Uvicorn**: An ASGI server for running FastAPI applications.
- **Facebook Scraper**: A library for extracting data from the Facebook platform.
- **OpenCV**: A library for computer vision and image processing.
- **PyTesseract**: A library for optical character recognition (OCR).
- **YOLO (You Only Look Once)**: A model for detecting objects in images.
- **Ultralytics**: A library for implementing YOLO models.
- **Supabase**: A database-as-a-service platform based on PostgreSQL.
- **Python-dotenv**: A library for managing environment variables.
- **BeautifulSoup**: A library for parsing HTML and XML.

## وصف التطبيق

AutoFinder هو تطبيق متكامل لاستخراج ومعالجة إعلانات السيارات من منصات التواصل الاجتماعي المختلفة مثل فيسبوك وتيك توك. يستخدم التطبيق تقنيات الذكاء الاصطناعي والرؤية الحاسوبية للتعرف على السيارات في الصور والفيديوهات، واستخراج المعلومات المهمة مثل الموديل، الشركة المصنعة، سنة الصنع، السعر، الموقع، رقم اللوحة، اللون، وأرقام الشاسي.

يوفر التطبيق واجهة برمجة تطبيقات (API) تتيح للمستخدمين البحث عن سيارات محددة باستخدام أرقام اللوحات أو أرقام الشاسي، مما يساعد في تسهيل عملية شراء وبيع السيارات المستعملة وتوفير معلومات دقيقة وموثوقة.

### كيفية عمل التطبيق

يعمل التطبيق من خلال الخطوات التالية:

1. **استخراج البيانات**: يقوم التطبيق بزيارة صفحات ومجموعات السيارات على منصات التواصل الاجتماعي واستخراج المنشورات التي تحتوي على معلومات السيارات.

2. **معالجة النصوص**: يستخدم التطبيق تقنيات معالجة اللغة الطبيعية لاستخراج المعلومات المهمة من نصوص المنشورات مثل الموديل، السنة، السعر، وغيرها.

3. **تحليل الصور**: يستخدم التطبيق نموذج YOLO للكشف عن السيارات في الصور، ثم يستخدم تقنيات الرؤية الحاسوبية لتحليل لون السيارة وخصائصها.

4. **استخراج النص من الصور**: يستخدم التطبيق تقنية OCR (التعرف الضوئي على الحروف) لاستخراج النصوص من الصور، مثل أرقام اللوحات.

5. **معالجة الفيديوهات**: يقوم التطبيق باستخراج إطارات من الفيديوهات ومعالجتها بنفس طريقة معالجة الصور.

6. **تخزين البيانات**: يتم تخزين جميع المعلومات المستخرجة في قاعدة بيانات Supabase.

7. **واجهة برمجة التطبيقات**: يوفر التطبيق واجهة API تتيح للمستخدمين البحث عن السيارات والوصول إلى المعلومات.

### التقنيات المستخدمة

- **FastAPI**: إطار عمل لبناء واجهات برمجة التطبيقات بلغة Python.
- **Uvicorn**: خادم ASGI لتشغيل تطبيقات FastAPI.
- **Facebook Scraper**: مكتبة لاستخراج البيانات من منصة فيسبوك.
- **OpenCV**: مكتبة للرؤية الحاسوبية ومعالجة الصور.
- **PyTesseract**: مكتبة للتعرف الضوئي على الحروف (OCR).
- **YOLO (You Only Look Once)**: نموذج للكشف عن الكائنات في الصور.
- **Ultralytics**: مكتبة لتنفيذ نماذج YOLO.
- **Supabase**: منصة قواعد بيانات كخدمة تستند إلى PostgreSQL.
- **Python-dotenv**: مكتبة لإدارة متغيرات البيئة.
- **BeautifulSoup**: مكتبة لتحليل HTML و XML.

