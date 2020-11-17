# Exercise 0
In this exercise, let's just setup a few things to have our environment ready to do the other exercises

## AWS account
- If you have not done so already, create an aws account

## AWS configure
- Once you have your aws account created, we need an IAM user that can generate an access Key ID & a Secret Access key
- Please follow this guide to create this user: https://docs.aws.amazon.com/IAM/latest/UserGuide/id_users_create.html#id_users_create_console
- Once the user has been created, we'll need their access key ID & secret Access key to do the next step
- Open a terminal and run (we're going to set up a specific profilee for this named learning)
```bash
aws configure --profile learning
AWS Access Key ID [None]: enter key id here
AWS Secret Access Key [None]: enter secret access key here
Default region name [None]: enter a default region
Default output format [None]: (you can leave this blank)
```

## Directory
- let's make this directory to hold all of our terraform work
```bash
mkdir terraform-learning
cd terraform-learning
```
