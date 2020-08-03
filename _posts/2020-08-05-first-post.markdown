---
layout: post
title:  "My First Post"
date:   2020-08-03 22:59:44 +0530
categories: jekyll update
author: "Pranav Kumar"
---

<strong class="strong" > H</strong> ello , this is my first post .Currently I am learning to create my own custom layout in jekyll . I think the answer lies either in index.html or .config . Lets see what this blog  becomes.  

I created this post by the following :
   * First I created a markdown file in `_post` directory having  
     name format of `Year-Month-Day-Post-Name.markdown .   
   * Then I added the **Front Matter** . This is .yml syntax is pretty easy .  
   ```
     ---  
     layout: post  
     title:  "Your Topic"  
     date:Year-Month-Day   
     categories: jekyll update  
     author: "Your Name"  
     ---  
     ```

After this I made some changes in my `_config.yml` file like github id ,description ,etc . It seems like this is the file which will change initial default data like title ,email ,etc . According to this file only the website  is rendered . Basically it configures the page as it's  name sugests

I will keep on updating as I move along .