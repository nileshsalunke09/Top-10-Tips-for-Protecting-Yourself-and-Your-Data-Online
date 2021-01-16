# **Top-10-Tips-for-Protecting-Yourself-and-Your-Data-Online**

# **Introduction**

No matter how strong your security may be, humans will be the primary attacking point. Learn how to protect yourself online, and by extension, your systems. Sharpen your awareness of social engineering techniques and how attackers gain access to systems.

# **Security misconceptions**

### What we think a primary target is.

![data-center.jpg]({{site.baseurl}}/data-center.jpg)


We feel that I have my acount on a platform and I am safe the platform like google is concerned about the safety and I have nothing to do with security. 

But in reality for hackers it is hard and a lot of work to break into a server or data center.

### The primary target is you.

![PIC2.jpg]({{site.baseurl}}/PIC2.jpg)

Humans to this day are the weakest link in the security chain. We have Intrusion detection systems, We have firewall strong password, SSL keys all are useless because of Humans.

Today we are going to see how we can not be the weakest link in the security chain.


# **Social engineering**

“Social engineering is a manipulation technique that exploits human error to gain private information, access, or valuables. In cybercrime, these “human hacking” scams tend to lure unsuspecting users into exposing data, spreading malware infections, or giving access to restricted systems”

In majority social engineering is how hacks are happening now a days.

Below are the examples of the people who got social engineered.

![Screen Shot 2021-01-16 at 12.53.12 PM.png]({{site.baseurl}}/Screen Shot 2021-01-16 at 12.53.12 PM.png)

Outside walls of twitter are secure like we saw the server and stuff is all secure, But the inside is where the security breach happens, All the hacker has to do is compromise one person and they get in and then you have vault clusters with no authentication, you have kafka with no authentication, And they can do anything.

### **Tip #10 - Use Key Based Auth Whenever Possible**

- Public Private key authentication is more secure than password auth.

- Whenever possible, use ppk auth (especially SSH).


### **Tip #9 - Beware of Sharing Too Much on the Internet**

![Screen Shot 2021-01-16 at 1.30.03 PM.png]({{site.baseurl}}/Screen Shot 2021-01-16 at 1.30.03 PM.png)

We find surveys on facebook and ads saying know your friends in detail and they request for the information

- What was your highschool name?

- What was the model of your first car?

- What is your favorite book?

- Where was your first international trip?

In reality above questions many other questions like this are used when you do your password recovery.

Many people have their facebook account public and hackers can easily google anyone's name and guess their email id's and guess thier password.

Now instead of a brutforce attempt where hackers try every possible letter combination which would take a long time the public account enables hackers to narrow their pool and put your account at risk.

### **Tip #8 - Have Backups and Be Able to Restore Them**

- A backup that’s never been restored isn’t a backup, it’s a prayer

- With the advent of Ransomware attacks this is more important than ever


### **Tip #7 - Beware of Phishing**

- “The fraudulent practice of sending emails purporting to be from reputable companies in order to induce individuals to reveal personal information, such as passwords and credit card numbers.”

- Always check who the email is from and where the links/buttons in the email link out to.

![Screen Shot 2021-01-16 at 1.47.42 PM.png]({{site.baseurl}}/Screen Shot 2021-01-16 at 1.47.42 PM.png)

![Screen Shot 2021-01-16 at 1.48.35 PM.png]({{site.baseurl}}/Screen Shot 2021-01-16 at 1.48.35 PM.png)

![Screen Shot 2021-01-16 at 1.48.59 PM.png]({{site.baseurl}}/Screen Shot 2021-01-16 at 1.48.59 PM.png)

### **Tip #6 - Protect Your Devices and Identity**

- Encrypt the disks on all your devices.

- Ensure you are logged off of your accounts, especially when using public computers.

- Lock your devices, physical access is root access.

How do I encrypt my disk/device?

In MacOS goto settings - encryption - encrypt the disk.

In Linux you can set it up when you do the installation.

In windows, You can use bitlocker.

Iphone/Android has encryption native to the operating system.

Mostly encryption is OFF by default, You have to set it to ON.

### **Tip #5 - Keep Your Software Updated**

- The longer a bug exists in the wild, the more likely it will be found.

- Keeping software up to date on servers and personal machines minimizes compromise


![Screen Shot 2021-01-16 at 1.58.46 PM.png]({{site.baseurl}}/Screen Shot 2021-01-16 at 1.58.46 PM.png)

### **Tip #4 - Change Default Passwords**

People buy security cameras, baby monotors and lots of other things that are connected to the internet and do not change the default password which makes them more prone to hacking.

Maintain password rotation cycle for all the devices.


![Screen Shot 2021-01-16 at 2.06.53 PM.png]({{site.baseurl}}/Screen Shot 2021-01-16 at 2.06.53 PM.png)


### **Tip #3 - Adopt a Principle of Least Privileges**

- Only those who need administrator access should get it.

- All resources/tools/data should be behind some form of authentication and authorization.

- Unless you need access to a resource, you don’t get it.

### **Tip #2 - Use Strong Passwords**

![Screen Shot 2021-01-16 at 2.17.22 PM.png]({{site.baseurl}}/Screen Shot 2021-01-16 at 2.17.22 PM.png)

### **Tip #1 - Use Two Factor Authentication (2FA)**

- Identity can be determined by one or more of the following.
	- Something you know.
    - Something you are.
	- Something you have

- Something you know.
	- Password, Passphrase.

- Something you are.
	- Fingerprint. 
	- Facial Scan.
	- Retina Scan.

- Something you have.
	- Ubikey.
	- Rotating Passcode (Google Auth, RSA Token)
	- SMS Message (be weary)
    
    

 **For more details please watch this [video](https://www.youtube.com/watch?v=ZAH9Bz7OdNI)**   







