---
theme: ./
title: Mokkapps Theme
favicon: logo.png
layout: cover
---

# A day of a front-end developer

<br/>
<a  href="https://b23.tv/2CwLsFQ">▶️</a>
<div class="pt-10">
  <span @click="next" class="px-2 p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>


---
layout: section
---
# Situation

- The Internet industry has been suffering a cold winter for several months.
- There are more job seekers than the HC(head count).
- Finding an ideal job now is more difficult than before.

<br>
<br>

<div v-click>> a foreign company</div>
<div v-click>> a remote work</div>
<div v-click  class="arrow">🔽</div>
<div v-click class="tips">good English communication skills</div>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
.tips {
  color:#2B90B6;
  font-size:14px;
}
.arrow{
  margin-left:50px;
}
</style>

<!--
Here is another comment.
-->

---
layout: section
---

# agreement

- try to express your words in English as much as possible.
- if you are not sure how to express something -

  you can describe it in another way or simply say some keywords
- the final option is chinese
- if there are any problems, you can say 'excuse me'...


---
layout: image-right
image: ./assets/words.jpg
---


# some pronuciation

<div>
  <br />
    <div class="title" v-click><span class="mr-10">model</span><span class="mr-10">modal</span><span>module</span></div>
    <div class="row">
      <span class="mr-8" v-click>/ˈmɒdl/<br />/ˈmɑdəl/</span>
      <span class="mr-8" v-click>/ˈməʊdl/</span>
      <span v-click>/ˈmɒdjuːl/<br />/ˈmɑʤul/</span>
    </div>
    <br />
    <br />
    <div class="title" v-click><span class="mr-10">router</span><span>route</span></div>
    <div class="row">
      <span class="mr-8" v-click>/ˈruːtə/<br />/ˈraʊtər/</span>
      <span v-click>/rut/<br />/raʊt/</span>
    </div>
    <br />
    <br />
    <div class="title" v-click><span class="mr-10">wrap</span><span>wrapper</span></div>
    <div class="row">
      <span class="mr-10" v-click>/ˈræp/</span>
      <span v-click>/ˈræpə/<br />/ˈræpər/</span>
    </div>
  </div>



<style>
.row {
  display:flex;
}
</style>

---
layout: image-left
image: ./assets/words.jpg
---
<div>
  <br />
  <div class="title" v-click>useEffect</div>
  <br />
  <div class="title" v-click>mock</div>
  <div class="row">
    <span v-click>/mɒk/<br />/ma:k/</span>
  </div>
    <br />
    <br />
  <div class="title" v-click><span class="mr-16">margin</span><span>plugin</span></div>
  <div class="row">
    <span class="mr-10" v-click>/ˈmɑrʤən/</span>
    <span v-click>/ˈplʌgɪn/</span>
  </div>
  <br />
  <div class="title" v-click>null</div>
  <div v-click>/nʌl/</div>
  <br />
  <div class="title" v-click>hook</div>
  <div v-click>/hʊk/</div>
  <br />
  <div class="row">
  <a v-click class="mr-10" href="https://stackoverflow.com/questions/3058246/which-is-the-correct-shorthand-regex-or-regexp">regex/regexp</a>
  <a v-click href="https://juejin.cn/post/6844903967856541710">MORE</a></div>
  </div>


<style>
.row {
  display:flex;
}
</style>



---
layout: about-me
---

---
layout: two-cols
---

<h1> 8:00 AM </h1>

<br/>
<div v-click="1">get up & have breakfast</div>
<br/>
<div v-click="2">commute to work</div>
<img v-click="1" class="rounded-full object-cover h-80 w-80 mt-10 border border-secondary-400 z-10" src="/assets/breakfirst.jpg" />

::right::


<img v-click="3" class="" src="/assets/check-emails.webp" />


<br/>
<div  v-click="3">open up my laptop & check emails</div>
<br/>
<div v-click="4">check the todo list & plan what to do today</div>
<br/>
<div v-click="5">check out the latest news in the dev community</div>
<br/>

<h1 v-click="3"> 9:00 AM </h1>



---
layout: image-right
image: ./assets/meeting.jpeg
---

# 9:30 AM

<br/>
<div class="tips">Daily Standup with my team</div>
<br/>
<br/>

<div class="dialog" v-click>Team Lead：<br/>morning everyone! As usual, let's give an update on what we've been working on, any blockers or concerns, and what we plan to work on next.</div>

<div v-click  class="arrow">🔽</div>

<div class="tips" v-click>morning everyone, so let's kick off</div>


---

<div class="dialog">
<div class="flex border px-4 py-2 rounded-md">
  <div class="mr-4">👦🏻:</div>
  <div>
  Yesterday, I worked on the home page for the project.<br/>
  30% is the progress, and no issues to report, all is fine. <br/>
  Today, I'm gonna keep working on it.
  </div>
</div>
<br/>
<div class="flex border px-4 py-2 rounded-md">
  <div class="mr-4">👧🏻:</div>
  <div>
  Refactored the ModalForm component by using antd5 yesterday<br/>
  and checked the cross-browser compatibility.<br/>
  All is fine except IE,but luckly, we don't need to consider this.<br/>
  Today, I'm gonna write unit tests for this component.
  </div>
</div>
<br/>
<div class="flex border px-4 rounded-md">
  <div class="mr-4">👧🏻:</div>
  <div>
  Yesterday, I was working on developing the product module<br/>
  and fixed an emergency bug on the production environment.<br/>
  Almost 60-70% I have completed on the product module.<br/>
  Today, I'm gonna integrate the APIs with our back-end teammates.
  </div>
</div>
</div>

---

<div class="dialog">
<div class="flex border px-4 rounded-md">
  <div class="mr-4">👦🏻:</div>
  <div>
    Yesterday I was working on developing a chart component for our project.<br/>
    And facing a performance issue when rendering large amounts of data - once the data hits 100,000, the chart component starts to render very slowly.<br/>
    I'll spend a little time on that today
  </div>
</div>
<br/>
<div class="flex border px-4 rounded-md">
  <div class="mr-4">👦🏻: </div>
  <div>
    I've been focusing on the front-end infrastructure in the past few days.<br/>
    I updated our build process by using the latest version of Webpack, <br/>
    and integrated a new CSS preprocessor to make it easier to write modular CSS.<br/>
    Today, I'm gonna improve our accessibility by adding ARIA attributes to our UI components.
  </div>
</div>
<br/>
<div class="flex border px-4 rounded-md">
  <div class="mr-4">👦🏻:</div>
  <div>
    Yesterday, I've been working on optimizing the performance of our database queries. <br>
    I found a couple of queries that were running slow, and made some changes that have improved the response time by 50%.<br>
    No roadblocks to report, and today I plan to work on adding some new features to our user dashboard.
  </div>
</div>
</div>

---
layout: two-cols
---


<div class="dialog border px-4 py-6 mr-10 rounded-md">
  Team Lead: all right, sounds good. anything else to discuss? let's go back to work
</div>

<div  v-click="1"  class="coding ml-50">coding time →</div>


::right::

<div v-click="1">
<h1  class="text-white text-center">10:00 AM</h1>
<img  class="mt-30 rounded-md" src="/assets/coding.jpeg" />
</div>



---

# coding

<div v-click class="tips"> a teammate talks to me </div>
<div class="dialog">
<div v-click class="flex">
  <div class="mr-4">teammate:</div>
  <div>
Hey, you mentioned the issue of chart rendering when dealing with large amounts of data. I've faced the same problem before. </div>
</div>
<div v-click class="flex">
  <div class="mr-4">👦🏻: </div>
  <div>
Really? How did you solve it?
  </div>
</div>
<div v-click class="flex">
  <div class="mr-4">teammate:</div>
  <div>
  The official Echarts documentation provides an attribute 'sampling',it can lower the sampling rate for rendering<br> 
  You can have a try, and turn off animations in the configuration
  </div>
</div>
<div v-click class="flex">
  <div class="mr-4">👦🏻:</div>
  <div>
Thank you, that's really helpful.
  </div>
</div>
<div v-click class="flex">
  <div class="mr-4">QA:</div>
  <div>
  You're welcome. If there are still some problems, you can discuss with the product manager whether you can load data in sections to reduce the amount of data being rendered.
  </div>
</div>
<div v-click class="flex">
  <div class="mr-4">👦🏻:</div>
  <div>
Okay, I'll give it a try.
  </div>
</div>
<div>
</div>
</div>


---

# coding

<div class="dialog">
<div class="flying-down">
  <img  class="w-80" src="/assets/screen-shot.png" />
</div>
<br/>
<br/>
<div v-click class="flex">
  <div class="mr-4">👦🏻:</div>
  <div>
Hello, the card content is arranged in three per row, but if the value is too big, the content will overflow the container or get squeezed down. Do you think we should use an ellipsis or come up with another solution?  </div>
</div>
<div v-click class="flex">
  <div class="mr-4">PM:</div>
  <div>
An ellipsis won't work because users need to see the results at a glance, and it's not user-friendly. Do you have any other ideas?
  </div>
</div>
<div v-click class="flex">
  <div class="mr-4">👦🏻:</div>
  <div>
    How about we change it to two per row instead?
  </div>
</div>
<div v-click class="flex">
  <div class="mr-4">PM:</div>
  <div>
    That's a great idea. Let's go with that.
  </div>
</div>
</div>


---
layout: image-left
image: ./assets/snap.jpg
---
# 12:00 PM
<br />
<br />
<br />
lunchTime & have a rest

---


# 1:30 PM 


<div v-click class="tips"> the quality assurance calls me </div>
<div class="dialog">
<div v-click class="flex">
  <div class="mr-4">QA:</div>
  <div>
Hey, I reported a bug in our app. It's not happening all the time, Can you take a look? </div>
</div>
<div v-click class="flex">
  <div class="mr-4">👦🏻: </div>
  <div>
  Sure, can you give me some more details about the issue and when it pops up?
  </div>
</div>
<div v-click class="flex">
  <div class="mr-4">QA:</div>
  <div>
Yeah, so it occurs when the user click the "submit" button on the form. Sometimes, the data doesn't save in the database, and there's no error message.
  </div>
</div>
<div v-click class="flex">
  <div class="mr-4">👦🏻:</div>
  <div>
Got it. Can you send me all the steps you're taking to recreate the issue, and I'll take a look at the code.
  </div>
</div>
<div v-click class="flex">
  <div class="mr-4">QA:</div>
  <div>Of course</div>
</div>
</div>


---

<div class="dialog">
<div class="tips">
  A few minutes later
</div>
<br/>
<br/>
<div v-click class="flex">
  <div class="mr-4">👦🏻:</div>
  <div>
Hey, I've been digging into the code, and I think I found the issue. It's just a small syntax mistake that's causing the data to not save occasionally. I've fixed it, and the next update should have the solution.  
  </div>
</div>
<div v-click class="flex">
  <div class="mr-4">QA:</div>
  <div>
 Awesome, that's great news! Have you already merged it into the test branch?
  </div>
</div>
<div v-click class="flex">
  <div class="mr-4">👦🏻:</div>
  <div>
    Yes
  </div>
</div>

</div>



---
layout: sfc
example: simple
---

# 3:00 PM

<div class="tips flying">👦🏻: can you review my code </div>



---
layout: image-right
image: ./assets/wrap-up.jpeg
---

#  5:30 PM 

<br />
<br />
<br />
<h3>wrap up the laptop 😄</h3>



---
layout: audio
---



# the tune



---
layout: outro
---

# Thanks


