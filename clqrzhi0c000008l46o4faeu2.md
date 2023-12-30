---
title: "Tips on how You can pass the AWS Certified Developer - Associate Exam"
datePublished: Sat Dec 30 2023 11:32:56 GMT+0000 (Coordinated Universal Time)
cuid: clqrzhi0c000008l46o4faeu2
slug: tips-on-how-you-can-pass-the-aws-certified-developer-associate-exam
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/hfiym43qBpk/upload/96bf89f93a3fe0ca5fc88d430305cc15.jpeg
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1703935941841/2888f82e-6f9c-40f9-8226-f75d125595cc.jpeg
tags: aws, aws-certified-solutions-architect-associate, aws-certified-developer-associate, aws-community-builder

---

### Introduction

The AWS Certified Developer - Associate is one of the best certifications you can get to boost your career in Cloud Engineering. If you're like me, you've probably been eyeing to get this certificate from a while.

I passed the AWS Certified Developer - Associate Exam recently, and I thought I'd help others by telling them how to get it in the best way possible. I'll go over tips, courses, mock tests in this blog. I'd also like to give you about an underrated tip I used to help me clear the exam. Let's start.

## Structure of the Exam

Let me first give you a rundown about the exam.

The exam is scored up to a 1000. You would need a minimum of 720 (72%) to clear the exam.

You will have 130 minutes to answer 65 questions.

A key point to include here is out of the 65, you will have 15 questions that are ungraded. These are experimental questions that AWS put to see if they are good for future exams. You will not know which questions are experimental, so it's best to prepare like you're writing 65 questions.

There are domains that the exam focuses on:

* Domain 1: Development with AWS Services (32% of scored content)
    
* Domain 2: Security (26% of scored content)
    
* Domain 3: Deployment (24% of scored content)
    
* Domain 4: Troubleshooting and Optimization (18% of scored content)
    

The scoring is not based on each domain, but on the overall exam. You'll be quizzed on AWS services that are deemed to be useful to developers. The questions are multiple choice based or selecting multiple options.

The questions are usually scenario based. You will be given a situation in a development project and would be required to choose the most optimal solution.

Here's a sample question from the exam.

**Q) A developer is working on an application that stores highly confidential data in a database. The developer must use AWS Key Management Service (AWS KMS) with envelope encryption to protect the data. How should the developer configure the data encryption to meet these requirements?**

**A)** Encrypt the data by using a KMS key. Store the encrypted data in the database.

**B)** Encrypt the data by using a generated data key. Store the encrypted data in the database.

**C)** Encrypt the data by using a generated data key. Store the encrypted data and the data key ID in the database.

**D)** Encrypt the data by using a generated data key. Store the encrypted data and the encrypted data key in the database.

**Answer**: D – Envelope encryption is the practice of encrypting plaintext data with a data key and then encrypting the data key under another key. You must store the encrypted form of the data key so that you can use the data key to decrypt the encrypted data in the database.

Here's an [extensive guide](https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Exam-Guide.pdf) that goes into detail about the services covered in the exam and an additional set of [sample questions](https://d1.awsstatic.com/training-and-certification/docs-dev-associate/AWS-Certified-Developer-Associate_Sample-Questions.pdf).

## Preparing for the exam

So, for the exam, there are various ways that you could use to learn. The great thing about writing the AWS Developer Associate Exam is that you have an extensive community that has an abundance of information to help you learn more about the services.

One of the best courses that you can use to prepare is [Ultimate AWS Certified Developer Associate 2023 NEW DVA-C02](https://www.udemy.com/course/aws-certified-developer-associate-dva-c01/). Stephane is a really good teacher and make you understand the core AWS services in an easy method. I have personally used it to help me learn about the services.

Of course, there are vast number of free courses that you can use to help you prepare. [Free Code Camp's](https://www.youtube.com/watch?v=RrKRN9zRBWs&pp=ygUlYXdzIGRldmVsb3BlciBhc3NvY2lhdGUgY2VydGlmaWNhdGlvbg%3D%3D) guide is a really good resource to help you learn about the services used in the exam.

I'd also encourage you to read up on white papers written by AWS. They are not mandatory; however, they provide a deeper understanding on how the services are used to help run applications.

Here's a list that I've found helpful.

* [AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html?did=wp_card&trk=wp_card)
    
* [DevOps Guidance](https://docs.aws.amazon.com/wellarchitected/latest/devops-guidance/devops-guidance.html?did=wp_card&trk=wp_card)
    
* [Blue/Green Deployments on AWS](https://docs.aws.amazon.com/whitepapers/latest/blue-green-deployments/welcome.html?did=wp_card&trk=wp_card)
    

You can also use notes that people have prepared to help you revise concepts once you have learnt the services. Here is a bunch of [notes](https://aws-dva-notes.shrithik.cloud/) that I took to help you prepare.

Feel free to use these really good resources as well.

* [Certified-aws-developer-associate-notes](https://github.com/itsmostafa/certified-aws-developer-associate-notes)
    
* [Tahseer's Notes](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa280RFJRY3V2ZnlQM3g1c3d0SDZlODZtbXNjd3xBQ3Jtc0tsenctUDJBWUZLVzNSWDdXY0htc2VCS1pGZzJfa3dzbHcteXRIYjlQRjEtTWtiRk83UVVTYm9UdVBjZVpiQjBTYm5vaW9RT3g4MTNXSngteFBUX1V6TkRMdk1XcVBwOUlfMUF3N3N3eU5hZFdEWmJXSQ&q=https%3A%2F%2Farkalim.notion.site%2FAWS-Developer-Associate-DVA-C02-aa44174fd7634a788368a85ec533e5fc&v=x88k9fuEDuE)
    

## Practice Exams

Practice exams are one of the best ways to help you prepare for the actual exam.

They help mimic the actual environment of the exam by making you take timed exams. After the exams, you will receive feedback on which questions you got wrong.

A lot of the questions on the practice exams are usually seen on the actual exam or they help you answer similar questions.

You can take some practice exams from this list.

* [Practice Exams | AWS Certified Developer Associate 2023](https://www.udemy.com/course/aws-certified-developer-associate-practice-tests-dva-c01/)
    
* [AWS Certified Developer Associate Practice Exam Questions](https://www.udemy.com/course/aws-developer-associate-practice-exams/)
    

Do not feel discouraged if you get a low score on your first time writing the exam (I got 49% on my first time lol). Remember, it's just to help you prepare for the exam.

I would like to advise you to keep taking the practice exams multiple times until you get &gt;80% consistently. It's a good benchmark to help you understand how prepared for your exam.

## Underrated Tip: Build Projects

A lot of people tend to forget the core reason of writing the AWS Developer Associate: To showcase your proficiency in using AWS services. But you can't show that you are skilled if you do not have any projects to prove it :)

Building projects is a really good way to show that you are skilled in using AWS services. It helps you get hands-on practice and also helps you learn a lot about how AWS services work. They indirectly help you prepare for the AWS Examination.

It's also a good way to prepare for any certification that you would want to work toward.

This approach made it easier for me to prepare for the Exam. I built several projects during my preparation that helped me explore a range of AWS services.

Here is a list of what I've built to help me practice.

* [Chapterify - A Youtube timestamp and summary generator](https://github.com/ShrithikShahapure/Chapterify)
    
* [Netmaze-Explorer - A terraform script that deploys a production level environment](https://github.com/ShrithikShahapure/netmaze-explorer)
    
* [Youtube-Data-Engineering - An end-to-end Data Engineering project](https://github.com/ShrithikShahapure/Youtube-Data-Engineering)
    
* [AWS-Cloud-Resume-Challenge - A popular beginner project](https://github.com/ShrithikShahapure/AWS-Cloud-Resume-Challenge)
    

## Conclusion

There you have it. This should be good enough to help you on your way to getting the AWS Developer certificate.

Try not to get too nervous during the exam, especially if it's the first time you're writing one. You'll have more that enough time to attempt all the questions.

When addressing the questions, avoid initially searching for the right answer. Instead, employ the elimination technique by pinpointing incorrect options and excluding them. Ultimately, focus on the questions, as they all include key terms that can guide you to the correct solution.

Thanks for reading my blog! Good Luck on your exam :)