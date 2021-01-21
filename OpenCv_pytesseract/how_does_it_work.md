# What it does 
## it opens zip files with images, process them using pytesseract engine to find text on the given image( in this case the images are newspapers pages ), prompts the user for input and search the image for that input, if the user input is found then it displays all the faces represented on the page where user input text is found using the OpenCV engine faceclisifier to detect faces.

# How does it work? 
## using binarization on the images so the tesseract engine can process and find text, using opencv funcitons and numpy array to convert img dtype so we can display our image using Python Imaging Lybrary (PIL)


### IT WORKS BUT ITS STILL SLOW, IT TAKES ABOUT FEW MINUTES TO PROCCES 4 IMAGES IN THE ZIP FILE(~50MB) 