# pdfextractor

Main solution is in qwenvlmpdfextractor.ipynb , we use qwen2vl 7b model to extract pdf to json with prompting.
We check accuracy of each prediction by compairing key values through extracted text.
Using VLM is much better than OCR because of layout detection as well as better vision encoder backbone in VLM.

First install all requirements given in the requirements.txt
Then unzip the test files , logic for conversion to images and then inference is given in relevant notebooks.
