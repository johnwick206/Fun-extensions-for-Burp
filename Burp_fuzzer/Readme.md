# Welcome all.

<p>This is a simple Burp extension written in Python, and I guess you know what BURP is; otherwise you won't bother opening this repo :).</p>
<p>At some point, you may find yourself attacking a web application or a web service that does not allow you to use traditional web application assessment tools.<br>
This is where it is useful to be able to leverage BURP to establish a solid baseline of HTTP Traffic, including 
  - authentication cookies
  - and many more ...

I worked on a Burp extension to create a simple web application fuzzer, which will be public so any insights from you guys reading this will be much appreciated.</p>

##### Reach me via LinkedIn or Email ;)

### Fire up BURP 
Before Firing up BURP, download a JAR file in your system: [Jython Standalone Installer](https://www.jython.org/download.html). Download the latest version and place it in a ***easy-to-remember*** location.

As the heading suggests get your BURP up and running. Greet the beautiful UI and go to the **Extender tab**.
Switch to **Options** and in the **Python Environment Section** select the location of your Jython JAR file, the file you just downloaded :).
![image](https://user-images.githubusercontent.com/63236771/117571061-8da26c80-b0ea-11eb-8e74-84dd136ac8e0.png)

### Play 

Load the given python file in the *Extensions tab*. Make sure to change the extension type to **Python**.
![image](https://user-images.githubusercontent.com/63236771/117571248-6009f300-b0eb-11eb-8623-5174a4342544.png)

Click Next and BURP will load our extension.
If there are errors, well go to the errors tab, debug any typos and close it.

The screen's gonna look like this
![image](https://user-images.githubusercontent.com/63236771/117571434-30a7b600-b0ec-11eb-9c96-64d63399baa6.png)

Well that's it, go to a vulnerable website and capture some requests.
Send to Intruder. 
You guys know how that works right, if not go and learn BURP first.

Now you are in the **Intruder tab**
Go to the **Payloads tab**, click **Payload Type** dropdown and select **Extension-Generated**.
In the Payload options click **Select Generator** and choose.
Then just Start the Attack and view the results.
They will be pretty interesting.


# Thank You






