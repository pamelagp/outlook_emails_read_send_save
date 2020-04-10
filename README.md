# outlook_emails_send_

This repository is for those who need to work with Outlook emails (.msg) either to: send, read, or get specific information about

I wrote this code because I needed to send  +50 personalized emails to +50 different companies and customers using my company's Outlook email in Windows (See the body of my email below)

I have an excel file with the relevant information such as CLIENT NAME, RECIPIENTS NAME, and some other information I needed to send.
I wrote the email template body in HTML and parse it with BeautifulSoup

My personalized email says:

TO: maik.ryvan@email.com
CC: myboss@ABCgroup.com, KeyAcountManager@ABCgroup.com
SUBJECT: BBB COMPANY - ABC GROUP - REQUEST FOR PRICES

Dear Mr. RECIPIENT NAME,
I am Elizabeth Aline, Marketing Specialist at ABC Group. 
Today I'm getting in touch regarding our client BBB Company. I need to request some prices.

Attached to this email, you will find: 
•	Attachement 1
•	Attachement 2
•	Attachement 3
•	Attachement 4 

If you have any questions, I will be happy to assist you.
Kind regards,

Elizabeth Aline
Marketing Specialist
elizabeth.Alineo@ABC.com
T: +999 (0) 5554545
 

