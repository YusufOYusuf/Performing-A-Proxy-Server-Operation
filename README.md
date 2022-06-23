<h1>Performing A Proxy Server Operation</h1>



<h2>Description</h2>
In this lab, I will perfrom a Proxy server operation. A proxy server is a server that intercepts requests being sent from a client and forwards those requests to their intended destination. The proxy server then sends any return traffic to the client that initiated the session. This provides address hidng for the client. 
<br />



<h2>Environments Used </h2>

- <b>Windows Server 2016 Standard</b> 



<h2>Program walk-through:</h2>

<p align="center">
From the desktop open up Google Chrome: <br/>
<img src="https://i.postimg.cc/g0XVLN3L/Screen-Shot-2022-06-22-at-11-11-43-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<br />
Navigate to the URL example.com </br>
<img src="https://i.postimg.cc/LsncYKyk/Screen-Shot-2022-06-22-at-11-13-33-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
You will observe the domain webpage</br>
<img src="https://i.postimg.cc/LXm0tcD0/Screen-Shot-2022-06-22-at-11-15-12-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Go to the search icon and type Internet Options:  <br/>
<img src="https://i.postimg.cc/fLgjYWHZ/Screen-Shot-2022-06-22-at-11-16-59-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<p align="center">
In the Internet Properties tab click Connections: <br/>
<img src="https://i.postimg.cc/pXVC47Fg/Screen-Shot-2022-06-22-at-11-18-54-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<br />
On the Connections tab, under Loacl Area Network (LAN) settings, click LAN settings </br>
<img src="https://i.postimg.cc/yN2NMk8k/Screen-Shot-2022-06-22-at-11-21-47-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
In the Local Area Network (LAN) settings dialog box, under Proxy server, check the Use a proxy server for your LAN checkbox and type Address then proceed by clicking ok twice: <br/>
<img src="https://i.postimg.cc/sDRqxyNq/Screen-Shot-2022-06-22-at-11-26-18-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br>
Go back to the browser window and click the Refresh icon to refresh the page:  <br/>
<img src="https://i.postimg.cc/wvp4vQWJ/Screen-Shot-2022-06-22-at-11-29-26-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  



<p align="center">
You will notice that the Example Domain will not load due to the proxy server setting done: <br/>
<img src="https://i.postimg.cc/kMFGBM5t/Screen-Shot-2022-06-22-at-11-30-45-PM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
