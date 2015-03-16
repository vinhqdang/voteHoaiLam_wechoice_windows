I wrote this small application to help Hoai Lam's fan can vote for him automatically on the website wechoice.vn

#How to use?

1. Install Java runtime. If you do not know how to, Google will help.

2. Modify *config.txt* for parameter. The most important one is timeout value. You should modify it based on your network status: slower network, higher timeout.

3. Modify *email.txt*: each line should contain one email address you want to use to register on vietid.

4. Run auto register: *java -jar AutoRegister.jar*. It will run through the *email.txt* file and register all email addresses there with same name and password provided in *config.txt*

5. Run auto vote with the same way.

##Note:
1. The program only support MS Windows.

2. The program is voluntary work. You take your own risk to use it.

###Good luck.
