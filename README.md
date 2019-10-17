# How to use AWS, AMAZON, Web Service

note to self(always ensure you do not upload your ssh file)

# What is AWS?
Amazon Web Service is the world's most comprehensive and boradly adopted cloud platform, offering over 165 fully featured services from data centers globally.



# Setting up AWS
- login to AWS
- create ec2 instance with all the settings required
-  Configure your instance
-  Connect your instance
- Getting Started with the AWS Command Line Tools

# What is dos2unix ?

The dos2unix command coverts plain text files Windows to Linux format

The unix2dos command coverts plain text files in Linux to Windows format

# Unziping dos2unix

- mv the doc2unix.exe to /bin/
- go into the place with provision.sh file on gitbash
- enter command
   - doc2unix.exe provision.sh

- move that provision file to
  - scp -i path/to/key file/to/copy user@ec2-xx-xx-xxx-       xxx.compute-1.amazonaws.com:path/to/file
  - moved the app directory using the same code
  - remember to -r

# SSH ubuntu

  - To copy files between your computer and your instance use an FTP service
  - scp -i path/to/key file/to/copy user@ec2-xx-xx-xxx-xxx.compute-1.amazonaws.com:path/to/file.
