# Setting Up the Lab Environment

* If you have any issues with your AWS account, install the similar version of CentOS (CentOS 7.3, http://vault.centos.org/7.3.1611/) to do the lab exercises on virtual machine, VMWare or Virtual BOX.
* The CentOS Project (https://www.centos.org/)

- This course includes a number of guided exercises and labs, which gives you an opportunity to practice the skills you learn in the course presentations. To complete these exercises, you will need to set up a practice system running Red Hat Enterprise Linux 7 that you completely control.
- One way to get access to a supported Red Hat Enterprise Linux system is to take advantage of Red Hat Enterprise Linux delivered by Amazon EC2 (Elastic Compute Cloud). Red Hat and Amazon Web Services collaborate to provide official Red Hat Enterprise Linux licensed images through Amazon’s on-demand public cloud service at free or low cost.
- The guided exercises and labs for this course were written assuming that you will set up an account with Amazon Web Services and use it to start a single, simple system running Red Hat Enterprise Linux 7. You will connect to that system securely over the internet and use it to practice commands.
- At the time of writing, Amazon Web Services provides an AWS Free Tier (https://aws.amazon.com/free/free-tier/) offering, which gives new users free access to certain sizes of cloud instances and operating environments (including Red Hat Enterprise Linux 7) for up to 750 hours per month, for 12 months.

## Important

- If you are not eligible for AWS Free Tier or have used up your free tier eligibility, a t2.micro-sized instance (cloud computer) running the same software, is currently estimated to cost between US$0.072 and US$0.08 per hour of compute time, depending on the data center in which the instance is started.
- To conserve compute time and any costs, make sure you shut down your cloud instance when you are not using it, and terminate (delete) it when you are completely finished with it.

## Lab Set-up Instructions

- Download Lab Set-up Instructions for Exercises on Amazon EC2 (https://github.com/andreluispro/curso-redhat/blob/master/Introduction/Setting-up-the-Lab-Enviroment/EdXLabInstructions_May18.pdf) and follow the steps to set up an AWS Free Tier account and to use it to launch a simple Red Hat Enterprise Linux 7 instance for the purposes of this course.

## Warning

- The security of your account, and of any cloud instances that you launch in Amazon EC2, is your responsibility. You are also responsible for charges you may incur, if any, by using this service. The instance that you are running is potentially visible to the public internet, and making changes to your default settings beyond those discussed in the course, such as running network services and opening ports in the firewall provided by AWS, or changing SSH server settings in the cloud instance, may have consequences for the security of the cloud instances you are operating.