<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Host a Website on Amazon S3

**Project Link:** [View Project](https://nextwork.ai/projects/70e2d059-31ab-5f67-8c58-f5edbd451140)

**Author:** versace  
**Email:** brian.nadanapatham@gmail.com

---

![Image](https://nextwork.ai/versacexgoose/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_5d4474f9)

## Introducing Today's Project!

### Project overview

In this project, I will demonstrate... my knowledge to host a website using Amazon S3. I'm doing this project to learn cloud and AWS fundamentals.

### Tools and concepts

Services I used were... Amazon S3. Key concepts I learnt include... buckets, ACLs, troubleshooting, bucket policies, and making a website.

### Time, challenges, and wins

This project took me approximately... 30 minutes. The most challenging part was... bucket policies. It was most rewarding to... learn how to create buckets for future use.

## How I Set Up an S3 Bucket

### What I did in this step

In this step, I will... create a bucket because... I want to create a storage space for my website files.

### How long it took to create the bucket

Creating an S3 bucket took me 2 minutes.

### Region selection

The Region I picked for my S3 bucket was... Canada central because it is the closest.

### Understanding bucket name uniqueness

S3 bucket names are globally unique! This means... no other AWS account in the entire world can use your bucket's name.

![Image](https://nextwork.ai/versacexgoose/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_ba6d42ad)

## Upload Website Files to S3

### What I did in this step

In this step, I will... upload the files into the S3 bucket because... it is a step to create a functional website.

### Files I uploaded

I uploaded two files to my S3 bucket - they were... index.html and Everyone...love_files.zip

### How the files work together

Both files are necessary for this project as... they house the necessary backend and frontend information for the website to function.

![Image](https://nextwork.ai/versacexgoose/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_a265af88)

## Static Website Hosting on S3

### What I did in this step

In this step, I will... make my website available on the internet because... I will set up static website hosting!

### Understanding website hosting

Website hosting means... you are storing your HTML file (and other files) on a web server.

### How I enabled website hosting

To enable website hosting with my S3 bucket, I... went to the General purpose buckets page, clicked properties, clicked edit on Static website hosting and enabled it.

### Access Control Lists (ACLs)

An ACL is... a set of rules that decides who can get access to a resource.

![Image](https://nextwork.ai/versacexgoose/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_c22c54c0)

## Bucket Endpoints

### Understanding bucket endpoint URLs

Once static website is enabled, S3 produces a bucket endpoint URL, which is... content from a static website stored in a cloud storage bucket.

### What I saw when I tested the endpoint

When I first visited the bucket endpoint URL, I saw... an error message. The reason for this error was... the files I uploaded are private.

![Image](https://nextwork.ai/versacexgoose/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_22ce4daf)

## Success!

### What I did in this step

In this step, I will... make my website files publicly acessible because... the website shows an error.

### How I resolved the 403 error

To resolve this 403 Forbidden error, I... made the objects public.

![Image](https://nextwork.ai/versacexgoose/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_5d4474f9)

## Bucket Policies

### What I did in this extension

In this project extension I'm about to... set up a bucket policy that stops people from deleted the index.html file. I'm doing this so that... it remains functional unless only I choose to delete it.

### Understanding bucket policies

An alternative to ACLs are bucket policies, which are... rules/actions that can be set to control more than just who can see/access an object. The benefit of using bucket policies is... that it gives you more control, while ACLs are useful for... providing a more limited way to grant basic read or write permissions to specific people or groups.

![Image](https://nextwork.ai/versacexgoose/uploads/70e2d059-31ab-5f67-8c58-f5edbd451140_sm2sm2sm)

### What my bucket policy does

My bucket policy... made it so the index.html file is not deletable. I tested this by... trying to delete the file and saw... an error (Access Denied).

---

*Built with [NextWork](https://nextwork.ai) - [View this project](https://nextwork.ai/projects/70e2d059-31ab-5f67-8c58-f5edbd451140)*
