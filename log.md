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


### Day 3: August 11, 2018

**Today's Progress:** I added TechLogo.vue component for displaying svg icons of technology stack on the main page. Wondering why my yesterday's deploy on Netlify shows an error 🧐 Localhosted works ok.

**Thoughts:** If my Vuetify module will not work with Netlify I consider making the Cards by myself in HTML/CSS. 

**Link to my site:** [Akcel.io](https://akcel.io)
**Link to the akcelio repo:** [akcelio GitHub repo](https://github.com/wbankowski/akcelio)


### Day 4: August 12, 2018

**Today's Progress:** I added a new front matter property "draft" which can have true/false value. If draft is true it means that it will not be visible on the post list. I have started answering some Node.js advanced questions what formed a new category in my blog.

**Thoughts:** I am still designing my BlogList component to fit perfectly into VuePress deafult theme. 

**Link to my site:** [Akcel.io](https://akcel.io)
**Link to the akcelio repo:** [akcelio GitHub repo](https://github.com/wbankowski/akcelio)


### Day 5: August 13, 2018

**Today's Progress:** Made some amendments to BlogList component. That's it for now with VuePress. Starting with Node.js project.

**Thoughts:** I am going to make a full CRUD Node.js app to show my understanding of the subject.

**Link to my site:** [Akcel.io](https://akcel.io)
**Link to the akcelio repo:** [akcelio GitHub repo](https://github.com/wbankowski/akcelio)


### Day 6: August 16, 2018

**Today's Progress:** I decided to make a classic Hangman game with Vue.js. Waiting for custom graphics from my daughter :) Need some customization of design. Tommorow I am going to finish it.

**Thoughts:** Used children components with $emit to parent. Took also a value of $event. Feel comfortable with regsitering components and using them within main App.vue

**Link to my site:** [Akcel.io](https://akcel.io)
**Link to the Vue Hangman repo:** [Vue Hangman GitHub repo](https://github.com/wbankowski/vue-hangman)


### Day 7: August 17, 2018

**Today's Progress:** Added getRandomWord method which uses async/await and fetch from [API Wordnik](https://api.wordnik.com/v4/words.json/randomWord). 

**Thoughts:** I have to wait to get api-key from Wordnik to access their API. Still need some work to catch and serve possible errors.

**Link to my site:** [Akcel.io](https://akcel.io)
**Link to the Vue Hangman repo:** [Vue Hangman GitHub repo](https://github.com/wbankowski/vue-hangman)
