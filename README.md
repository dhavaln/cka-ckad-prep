# Certified Kubernetes Administrator and Developer Notes
How I prepared for Kubernetes ~~CKA~~ and CKAD Certification Exams.

## Pretext
I already run and consult multiple environments using AWS ECS and Fargate. It serves the production and eventually I think we all will be either using Containers or Serverless technologies for most of the workloads. My personal interest on Kubernetes grew last year after spending some time with Docker. I work across teams and products, so having a full knowledge of "best" technology makes sense to take better decisions. 

I took the best decision and I enjoyed every bit of my journey so far. 

### If you don't love it, you are going to fail. - STEVE JOBS

## Books

[Cloud Native DevOps with Kubernetes by John Arundel and Justin Domingus](https://www.amazon.in/Cloud-Native-DevOps-Kubernetes-Arundel/dp/1492040762/ref=sr_1_2?crid=3JJ9LAE2E6L4W&keywords=cloud+native+devops+with+kubernetes&qid=1581853061&sprefix=cloud+native+dev%2Caps%2C280&sr=8-2) This is the best book that I have read in a recent time. It's well written and covers I think all of the Kubernetes in Production environment concepts really well. You will also see a list of tools from the Kubernetes Landscape with right examples. 

[Kubernetes Patterns by Bilgin Ibryam & Roland Hub](https://www.amazon.in/Kubernetes-Patterns-Bilgin-Ibryam/dp/1492050288/ref=sr_1_1?crid=1UW6WTYF33K2&keywords=kubernetes+patterns&qid=1581853405&sprefix=kubernetes+patt%2Caps%2C262&sr=8-1) Going throguh this book was my personal choice, rather than a suggestion. I have built softwares that run on Blade Servers, Colo clouds, virtual machines, and even with Serverless. Understanding the patterns is a important aspect as it will help me design better systems with Kubernetes instead of just rolling out containers. 

[Kubernetes Up and Running by Brendan Burns, Kelsey Hightower, Joe Beda](https://www.amazon.in/Kubernetes-Running-Future-Infrastructure-Second/dp/935213916X/ref=sr_1_1?crid=3J5CNJZIT350&keywords=kubernetes+up+and+running&qid=1581853574&sprefix=kubernetes+up%2Caps%2C274&sr=8-1) This one was an easy choice, Brendan Burns and Joe Beda are the co-creators of Kubernetes, nothing more to explain here. It's very unlikely that if you are working around Kubernetes and you have not come across a talk or a blog post of Kelsey Hightower.  

[Kubernetes Best Practices by Brendon Burns, Eddie Villalba, Dave Strebel & Lachlan Evenson](https://www.amazon.in/Kubernetes-Best-Practices-Blueprints-Applications/dp/9352139364/) This is another great book from Brendon Burns, co-creator of Kubernetes. As the title says, this is a pretty good reference book for best practices around running Kubernetes in production and at scale. From setup, security, monitoring, logging, and customizations, you will need it all while managing your clusters. It's a small book, with around 220 pages, but lot of good detailing. 

**Btw, I purchased print copies of some of the books to support print media, and I still like physical books ;)**

## Videos

Towards the end of my preparation, I did go through both the courses of [Mumshad Mannambeth](https://www.udemy.com/user/mumshad-mannambeth/) on Udemy.com. 
https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/
https://www.udemy.com/course/certified-kubernetes-application-developer/

## Practice 

You will have to practice a lot, or atleast that was the case for me. I am a slow learner, the more I practice the more I learn. Part of my day job requires me to spend time on multiple projects, containers, serverless, micro-services, AWS cloud, in general. 

Minikube is best setup to start with. However I would highly recomment using EKS or GKE to do better practice with varying setup. 

Create some sort of dummy application which can cover most of the Kubernetes primitives, that way you can relate to a real-world application easily. 

## From Borg to Kubernetes 
https://kubernetes.io/blog/2015/04/borg-predecessor-to-kubernetes/
> Kubernetes is conceptually derived from Borg, an internal container orchastration system used by Google. It is considered a "simplified" system to manage the most "complicated" environment. 

It will not be easy, but at the same time, you get a chance to learn how complicated systems are managed.

## Exam Updates

*  Cleared CKAD on 30th April, 2020
