Newspaper Article Segregator and OCR
This project uses a deep learning model to detect and segregate articles in a newspaper, then extracts and reads the content using Tesseract OCR. The model leverages Detectron 2 to create bounding boxes around each article, ensuring accurate detection and separation of the articles. Once the articles are detected, Tesseract OCR is used to convert the content into readable text.

Key Features:
Detectron 2 for Object Detection: Detects and segregates individual articles within a newspaper.
Tesseract OCR Integration: Reads and extracts text from each detected article.
Accurate Segregation: Capable of processing newspapers with multiple columns and irregular layouts.
Scalable Model: Can be adapted to different newspaper formats and structures.

Technologies Used:
Python
Detectron 2 for object detection
Tesseract OCR for text extraction
OpenCV for image pre-processing
