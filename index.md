# Hello 
## Hi 
###### Bye

Just tried creating headers of different sizes.

### Image of AI
![Image of AI](https://www.neilsahota.com/wp-content/uploads/2022/09/What-is-AI-how-does-it-work.jpg)


# Construct the relative path to tesseract.exe
tesseract_path = os.path.join(script_dir, "Tesseract-OCR", "tesseract.exe")
# Set the tesseract_cmd to the constructed path
pytesseract.pytesseract.tesseract_cmd = tesseract_path
