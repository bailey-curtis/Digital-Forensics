# Digital Forensics
<h2>Scenario</h2>
<br>
<br>
<h2>Instructions</h2>
You've examined and documented quite a bit of information from the iPhone image file. Now, you will use that documentation to build a final report. Before you complete your report, there is still some additional evidence to analyze. Since the internal investigators knew that Peter was close with Rosie, they collected Rosie's phone for your to analyze to determine if she in fact a co-conspirator.
<br>
<br>
Within Autopsy, on the top left, select the option "Add Data Source" .
<br>
<br>
Add Rosie's iphone image using the same process as Peter.
<br>
<br>
Analyze the following evidence on Rosie's phone.
<br>
<br>
View sms messages
<br>
<br>
Are there any additional sms messages which correlate Rosie to the crime?
<br>
<br>
Export Attachments on sms messages
<br>
<br>
Expand the attachments folder under sms until you find a .HEIC file and a .MOV file
<br>
<br>
Export those 2 files
<br>
<br>
Analyze the .MOV file
<br>
<br>
Access the .MOV file from your terminal, and run the following command xdg-open <filename>.MOV
<ul>
  <li>Did this file contain any evidence?</li>
  </ul>
<br>
Determine Geographic Data on the HEIC file. (Note: HEIC is Apple’s proprietary file type for photos)
<br>
<br>
Open a web browser within your Kali Terminal
Browse to https://onlineexifviewer.com/ and upload the .HEIC file
<br>
<br>
Analyze the data and determine the location where the photo was taken.
<br>
<br>
<h2>Bonus - Determining the Ring Leader of the Operation</h2>
Throughout the week, there were mentions that there was a ring leader secretly behind the operations of this crime. Additionally there are rumors this person is called Mr X. Can you determine who is Mr X?
<ul>
  <li>Hint 1 - You may have to listen to this evidence on your local computer as Kali doesn't always play sound.</li>
  <li>Hint 2 - Look for this evidence you want to listen to, on Peter's phone.</li>
</ul>
