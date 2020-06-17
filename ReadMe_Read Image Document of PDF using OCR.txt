It is a ready workflow, which can read a image file (scanned document) saved as PDF0 using OCR.

To Run the File:

- Extract the file and save this in location, preferably in UIPath folder of your machine
- Open UI Path Studio
- Show the downloaded file path
- Select on 'Project' file 
- Click on 'main.xaml' under Project Tab
- Save in your local machine
- Run/Debug
-------------------------------------------------------------------------------------
Before you start:

- In the "Read PDF with OCR" box, you show the path of the File (obviously in PDF format)- inside which
there is a scanned file,saved as Image in that PDF File,
- Then in the "Write text File" Box, Show the path of the Notepad (.txt file) file, 
where you want to save the text content extracted from the PDF Image via OCR.
---------------------------------------------------------------------------------

-You can Change the OCR engine- to increase the efficiency /correctness of the extracted value.
Here , In demo, I have used Microsoft ORC. You can Use Abbyy or Google OCR as well.
- You can save the extracted file in Word/ Excel file as well intead of Notepad. In that case, you have to
choose write to word or write to excel scope from the activity pane.

--------------------------------------------------------------------------------------------

For any confusuion, suggestion: redwan.contact@gmail.com

The Canvas was developed in UI Path Studio, Version: 2020.4.1


Developed By:

Redwan Ferdous Farhan
Dhaka, bangladesh
May 17th, 2020