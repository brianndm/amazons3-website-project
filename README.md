# Amazon S3 Website Project

## Project Overview

This project was made to learn about AWS, specifically Amazon S3. The goal of this project was to host a working website using Amazon S3.

## Tools and Concepts

Tools used were Amazon S3. Concepts learnt include creating, managing, and deleting buckets, ACLs, troubleshooting, bucket policies, and making a website in this new environment. 
This project took around 30 minutes and the most rewarding concepts to learn were managing buckets and creating bucket policies. 

## Setting Up an S3 Bucket

Before anything, the most optimal region was selected which was Canada central. Throughout the setting up process, a key takeaway was that S3 bucket names are globally unique. A bucket was created called "website-project-brian" and two objects were uploaded into the bucket (html file and folder). Both files house the necessary backend and frontend information for the website to function. 

## Enabling Website Hosting

Enabled website hosting by navigating through the properties tab in the buckets page and changed static website hosting from disabled to enabled. 

## Troubleshooting

After clicking the bucket endpoint URL, there was an error message. The error was quickly identified since the files were never set to public. To fix this, the objects were selected and made public.

## Bucket Policies

A concept called bucket policies interested me throughout the process of making the website. Because of this, a bucket policy was made that stops people from deleting the index.html file. This was done to prevent the deletion of the file from anyone. Another key takeaway from this project was that bucket policies were an alternative to ACLs which give more control.

## Deletion

After successfully launching and testing the website, I deleted the S3 bucket and its contents to prevent potential unexpected AWS charges in the future.
