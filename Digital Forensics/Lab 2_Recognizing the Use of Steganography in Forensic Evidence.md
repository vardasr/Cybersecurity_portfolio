# Overview
The Setting of this lab is an ongoing investigation into the activities of Beverly Gates, the HR Manager at Intricate Solutions, Inc. Senior leadership has reason to believe that Beverly is involved in a sophisticated drug trafficking operation and has recently brought in the police to investigate the matter further. As a forensic analyst working with the police, you have been given a drive image taken from Beverly's work laptop and tasked with reviewing its contents for forensic evidence of suspicious activity.
## Challenge
In this lab, I will use a variety of free tools to discover possible steganographic activity in image and audio files located on a suspect's drive image. I will properly identify and extract embedded data in a carrier image and document my findings.
## Methods
* (Section 1 Part 1) I will use Paraben's E3 and specialized hash database to search for steganography tools on the suspect's drive image. My challenge was to detect steganography software on a drive image using the evidence that was collected.
* (Section 1 Part 2) I will use the StegExpose command line stegnalysis tool to detect the use of LSB steganography in image files, which ones appear to contain steganographically - concealed files.
* (Section 1 Part 3) I will use OpenPuff's unhide data function to retrieve the hidden file. However, I will first need to obtain the passphrase and/or encryption algorithm that were used to encrypt the file.
* (Section 2 Part 1) I will use a different hash database to detect additional steganography software on the suspect's drive image.
* (Section 2 Part 2) I will again employ the StegExpose steganalysis tool to detect steganographic implants, first I will export evidence - in this case, a series of image files- from an E3 case file. then I will use the StegExpose tool to assess whether any part of these image files contain hidden data.
* (Section 2 Part 3) I will use the S-tools and Xiao applications.
* (Section 3 Part 1-2) I had to detect more hiddeen data and extract the hidden data that another analyst was working on but lacked the tools and the experience to retrieve it.
## Summary
For this lab I had three important concepts to learn and do. For the first part I had to detect steganography software on a drive image using E3. While doing this I had to extract hidden data using the command prompt. The second concept to learn was learning more about the tools OpenPuff, S-Tools, and Xiao applications seeing if I can extract the the hidden data from files. The last concept of this was trying to put it all together and helping out another analyst who is less skilled and has lack of tools 

[2_Recognizing_the_Use_of_Steganography_in_Forensic_Evidence_4e_-_Ren_Vardas (1).pdf.docx](https://github.com/user-attachments/files/26168262/2_Recognizing_the_Use_of_Steganography_in_Forensic_Evidence_4e_-_Ren_Vardas.1.pdf.docx)
