# 100 Days Of Code - Log

### Day 1: August 9, 2018

**Today's Progress:** Wanted to start a blog using Vue, so I configured site with VuePress and deployed it on Netlify. Modified config.js script to automaticaly generate Sidebar from YAML Front Matter metadata of each .md file in /docs/blog/ directory. I described the process [here](http://akcel.io/blog/Day1.html) 

**Thoughts:** A lot of array and object modification which learnt me a lot. I had to use additional modules like glob and front-matter. Next step is to create Vue component which displays as a grid of cards every single post located in /blog/ directory.

**Link to my site:** [Akcel.io](https://akcel.io)
**Link to the akcelio repo:** [akcelio GitHub repo](https://github.com/wbankowski/akcelio)
**Link to the config.js:** [config.js](https://github.com/wbankowski/akcelio/blob/master/docs/.vuepress/config.js)


### Day 2: August 10, 2018

**Today's Progress:** I added BlogList.vue component and added Vuetify as a dependency. I used Vuetify card element for making a grid of posts. Used v-for directive for generating dynamic content. It works perfectly. 

**Thoughts:** Because Vuetify is quite new for me, it took me a while to style my card element. Still need some fontawesome elements to display on my card. I have to add it as a dependency.

**Link to my site:** [Akcel.io](https://akcel.io)
**Link to the akcelio repo:** [akcelio GitHub repo](https://github.com/wbankowski/akcelio)
