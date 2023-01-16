# Braille-display
A Python code which I wrote during my final semester of college in 2019 to capture images of textbooks, extract the text and display each character in Braille representation with the help of servo motor actuators.

We have come across people with visual impairment willing to get an education, the only hindrance being the inability to read books. We aim at being the bridge between them and the books through our device. 
This project aims at creating a braille display using raspberry pi, a camera module that captures the image, Pytesseract ocr library that helps in extracting texts from the captured image and Sequential codes assigned to each character that helps in working of the actuators. 
Raspberry pi is the processor that facilitates all the processes including but not limited to, image processing, image to text conversion, actuators controlling. The Pi cam module is responsible for capturing image of the printed textbook; this acts as the eye of the device. The exquisite library which is used to extract text from the captured image is Pytesseract it is an OCR library.
