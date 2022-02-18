# My_Project
1.	The program will take longer URL link and return a shortened version of it
2.	We call these shortened aliases “short links.” Users are redirected to the original URL when they hit these short links. Short links save a lot of space when displayed, printed, messaged. Additionally, can remember the URL, Easy to maintain, can use the links where there are restrictions in text length
3.	URL shortening is used for optimizing links across devices tracking individual links to analyze audience and campaign performance, and hiding affiliated original URLs.
4.	We can add feature Auto expiry links to increases the performance, since we’re storing billions of rows NoSQL would be easier to scale
5.	To scale out our DB, we can use partitions concept by this we can increase the performances of DB
6.	The DB may crash for various reasons we can do replicas We can even combine certain less frequently occurring letters into one database partition.
7.	There can be multiple users inserting the same URL at the same time. We can control this with a lock.
8.	We can add feature Caching, by this when the application servers, before hitting backend storage we can quickly check if the cache has the desired URL and We can add a Load balancing.

Please find sample images:

<img width="575" alt="Screen Shot 2022-02-18 at 12 11 46 AM" src="https://user-images.githubusercontent.com/62187417/154629216-fc09d600-6c00-4ab4-9f87-2c120a7cebee.png">
<img width="600" alt="Screen Shot 2022-02-18 at 12 12 04 AM" src="https://user-images.githubusercontent.com/62187417/154629237-276df4b2-0c03-4b3a-902b-409b7b104c22.png">
<img width="584" alt="Screen Shot 2022-02-18 at 12 12 21 AM" src="https://user-images.githubusercontent.com/62187417/154629258-143618a3-eafb-4bf9-a134-3a8a51a15456.png">
<img width="1120" alt="Screen Shot 2022-02-18 at 12 15 45 AM" src="https://user-images.githubusercontent.com/62187417/154629282-d4c8b8da-12da-4524-b003-9f46f279f51d.png">
