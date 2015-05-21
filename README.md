# Send Email without Intent in Android


Send Email without Intent in Android.
	
This is a Library project.
With the help of this, user can able to send emails to single or multiple recipients with attachment.	
Method:-
	1. Add this library project to your application where you want to use this functionality.
	2. Import required class files.
	3. Create a object of GMailSender class using constructor passing  'mail id' and 'password'        
                  from which you want to send email.
	4. You can add attachment using addAttachment() method passing file name(optional).
	5. Use sendMail() method to send email.

Note:- Sender must have a gmail id.	

Code :-
	
	GMailSender sender = new GMailSender("sender_mail_id", "sender_password");
	sender.addAttachment(filePath1);
	sender.addAttachment(filePath2);					
sender.sendMail("Subject","Message","sender_mail_id","recipient_mail_id1, recipient_mail_id2");

Developed By:-
Pravin D. Shinde (pravin86.shinde@gmail.com)
