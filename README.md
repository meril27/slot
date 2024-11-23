# Ex03 Time Table
## Date:23.11.2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
<pre><code>
&lt;html&gt;
&lt;head&gt;
&lt;center&gt;
&lt;img src=&quot;/static/logo.png&quot; height=&quot;100&quot; width=&quot;630&quot;&gt;
&lt;/center&gt;&lt;br&gt;
&lt;title&gt;
&lt;b&gt;SLOT TIMETABLE - MERIL GOLDLINA A (24007299)&lt;/b&gt;
&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;table border=&quot;2&quot; cellpadding=&quot;10&quot; bgcolor=&quot;AntiqueWhite&quot; width=&quot;630&quot;&gt;
&lt;tr&gt; 
&lt;th bgcolor=&quot;silver&quot;&gt;Day/Time&lt;/th&gt;       
&lt;th bgcolor=&quot;white&quot;&gt;8.00 - 10.00&lt;/th&gt;
&lt;th bgcolor=&quot;silver&quot;&gt;10.00 - 12.00&lt;/th&gt;
&lt;th bgcolor=&quot;white&quot;&gt;1.00 - 3.00&lt;/th&gt;
&lt;th bgcolor=&quot;silver&quot;&gt;3.00 - 5.00&lt;/th&gt;
&lt;/tr&gt;
&lt;tr&gt; 
&lt;th bgcolor=&quot;white&quot;&gt;Monday&lt;/th&gt;
&lt;td bgcolor=&quot;LightCoral&quot; align=&quot;center&quot;&gt;-&lt;/td&gt;
&lt;td bgcolor=&quot;yellow&quot; align=&quot;center&quot;&gt;FWAD&lt;/td&gt;
&lt;td bgcolor=&quot;pink&quot; align=&quot;center&quot;&gt;BEEE&lt;/td&gt;
&lt;td bgcolor=&quot;LightCoral&quot; align=&quot;center&quot;&gt;-&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;th bgcolor=&quot;silver&quot;&gt;Tuesday&lt;/th&gt;
&lt;td bgcolor=&quot;LightCoral&quot; align=&quot;center&quot;&gt;-&lt;/td&gt;
&lt;td bgcolor=&quot;violet&quot; align=&quot;center&quot;&gt; Maths&lt;/td&gt;
&lt;td bgcolor=&quot;NavajoWhite&quot; align=&quot;center&quot;&gt;Chemistry&lt;/td&gt;
&lt;td bgcolor=&quot;LightCoral&quot; align=&quot;center&quot;&gt;-&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;th bgcolor=&quot;white&quot;&gt;Wednesday&lt;/th&gt;
&lt;td bgcolor=&quot;LightCoral&quot; align=&quot;center&quot;&gt;-&lt;/td&gt;
&lt;td bgcolor=&quot;yellow&quot; align=&quot;center&quot;&gt;FWAD&lt;/td&gt;
&lt;td bgcolor=&quot;PaleGreen&quot; align=&quot;center&quot;&gt;Mentor Meet&lt;/td&gt;
&lt;td bgcolor=&quot;LightCoral&quot; align=&quot;center&quot;&gt;-&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;th bgcolor=&quot;silver&quot;&gt;Thursday&lt;/th&gt;
&lt;td bgcolor=&quot;LightCoral&quot; align=&quot;center&quot;&gt;-&lt;/td&gt;
&lt;td bgcolor=&quot;LightSkyBlue&quot; align=&quot;center&quot;&gt;C Programming&lt;/td&gt;
&lt;td bgcolor=&quot;pink&quot; align=&quot;center&quot;&gt;BEEE&lt;/td&gt;
&lt;td bgcolor=&quot;LightCoral&quot; align=&quot;center&quot;&gt;-&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;th bgcolor=&quot;white&quot;&gt;Friday&lt;/th&gt;
&lt;td bgcolor=&quot;NavajoWhite&quot; align=&quot;center&quot;&gt;Chemistry&lt;/td&gt;
&lt;td bgcolor=&quot;gold&quot; align=&quot;center&quot;&gt;DE&lt;/td&gt;
&lt;td bgcolor=&quot;LightSkyBlue&quot; align=&quot;center&quot;&gt;C Programming&lt;/td&gt;
&lt;td bgcolor=&quot;LightCoral&quot; align=&quot;center&quot;&gt;-&lt;/td&gt;
&lt;/tr&gt;
&lt;tr&gt;
&lt;th bgcolor=&quot;silver&quot;&gt;Saturday&lt;/th&gt;
&lt;td bgcolor=&quot;gold&quot; align=&quot;center&quot;&gt;DE&lt;/td&gt;
&lt;td bgcolor=&quot;violet&quot; align=&quot;center&quot;&gt;Maths&lt;/td&gt;
&lt;td bgcolor=&quot;yellow&quot; align=&quot;center&quot;&gt;FWAD&lt;/td&gt;
&lt;td bgcolor=&quot;LightCoral&quot; align=&quot;center&quot;&gt;-&lt;/td&gt;
&lt;/tr&gt;
&lt;/table&gt;
&lt;table border=&quot;2&quot; cellpadding=&quot;10&quot; bgcolor=&quot;white&quot;&gt;&lt;br&gt;
&lt;tr&gt; 
&lt;th&gt;S.No.&lt;/th&gt;  
&lt;th align=&quot;centre&quot;&gt;Subject Code&lt;/th&gt;     
&lt;th align=&quot;centre&quot;&gt;Subject Name&lt;/th&gt;  
&lt;/tr&gt;   
&lt;tr&gt;
&lt;th&gt;1.&lt;/th&gt;
&lt;td align=&quot;centre&quot;&gt;19AI414&lt;/td&gt;
&lt;td&gt;Fundamentals of Web Application Development(FWAD)&lt;/td&gt;
&lt;/tr&gt; 
&lt;tr&gt;
&lt;th&gt;2.&lt;/th&gt;
&lt;td align=&quot;centre&quot;&gt;19CY205&lt;/td&gt;
&lt;td&gt;Principles of Chemistry in Engineering(CHE)&lt;/td&gt;
&lt;/tr&gt;   
&lt;tr&gt;
&lt;th&gt;3.&lt;/th&gt;
&lt;td align=&quot;centre&quot;&gt;19EE404&lt;/td&gt;
&lt;td&gt;Digital Electroincs(DE)&lt;/td&gt;
&lt;/tr&gt;   
&lt;tr&gt;
&lt;th&gt;4.&lt;/th&gt;
&lt;td align=&quot;centre&quot;&gt;19A1304&lt;/td&gt;
&lt;td&gt;Fundamentals of C Programming(C progm)&lt;/td&gt;
&lt;/tr&gt;   
&lt;tr&gt;
&lt;th&gt;5.&lt;/th&gt;
&lt;td align=&quot;centre&quot;&gt;19A1305&lt;/td&gt;
&lt;td&gt;Basic Electrical, Electronics and Measurement Engineering(BEEE)&lt;/td&gt;
&lt;/tr&gt;   
&lt;tr&gt;
</code></pre>
  
## OUTPUT
![alt text](<Screenshot 2024-11-23 140434.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
