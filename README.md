# Email URL Analysis

<h2>Description</h2>
In this email URL analysis, I exam a suspicious email's attached URL button, use sublime text editor to find the hyperlink url buton, use cyberchef to extract and defang urls, and showcase different OSINT url analysis tools to examine a live URL.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>Linux CLI</b>
- <b>Sublime Text Editor</b>
- <b>cyberchef</b>
- <b>phishtank</b>
- <b>urlscan</b>
- <b>url2png</b>
- <b>wannabrowser</b>

<h2>Environments Used </h2>

- <b>Unbuntu</b> 

<br />
<br />
Suspicious email from past example with a url link.   

![1) suspicious email and hyperlink buton](https://github.com/user-attachments/assets/eb8e340c-7e05-4b8f-9745-500420358536)

<br />
<br />
In sublime text editor, control find http to find http sources within body text, [<]a in html shows the "reactiveate acount" button along with its associated link. 

![2) subl txt ctl f http  a html hyperlink reactive account](https://github.com/user-attachments/assets/88f5f5aa-e717-47ff-a6d2-3420663cd820)

<br />
<br />  
Uploading the captured email file as input in cyberchef to filter from quoted-printable known from sublime text investigation, extract urls, and defang urls to malicious sites. 

![3) cyberchef, open file as input, from quoted, extract urls, defang urls](https://github.com/user-attachments/assets/bda4663b-9214-4798-82a9-a32c3ac845e0)

<br />
<br />
Using an email ioc extractor from malwarecube from github can extract similar results from the malicous email (https://github.com/MalwareCube/Email-IOC-Extractor).

![4) similar result with python ioc script by malwarecube](https://github.com/user-attachments/assets/5feb9de4-90eb-4d82-a9d1-f4fee21e1f3c)

<br />
<br />
Using phishtank, I selected a link url link to exam. 

![5 1) phishtank showcase of live urls](https://github.com/user-attachments/assets/7b5633e8-a297-400a-9dc9-511bbf27513c)

<br />
<br />
URLscan shows a summary of the submitted url along with ownership and main ip. 

![5 2) urlscan showcase, shows main ip and ownership](https://github.com/user-attachments/assets/6efbad7f-3a13-464c-b5f4-05b24bc1110b)

<br />
<br />
URL2PNG shows a screenshot of the submitted url to investigate the site without actually visiting it. 

![5 2) usl2png showcase, shows a google credential capture phish](https://github.com/user-attachments/assets/3674eb37-7963-4644-9471-27b47e4a4dff)

<br />
<br />
Lastly, wannabrowser can extract site headers and body text without having to visit the site.  

![5 3 wannabrowser showcase](https://github.com/user-attachments/assets/3e07acc5-f9e2-4be2-84b4-3869a16ea92c)<br />
<br />
