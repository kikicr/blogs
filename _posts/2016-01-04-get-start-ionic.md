---
layout: post
title: "getting started ionic framework"
quote: "some beautiful ways to make hybrid mobile apps"
image:
      url: /blogs/assets/images/get-start-ionic/cover.png
      
      
video: false
comments: true
theme_color: 302F2D
---
# ionic framework 
ionic framework is the beautiful ways to make an hybrid mobile apps,by using html,css,and js that base on angular + cordova
.so we can implement mvw (model view whatever) like mvvm or mvc here.

## installation

### install npm

First, install <a href="http://nodejs.org/">Node.js 4</a> (Node 5 does not work at the moment!). 
Then, install the latest Cordova and Ionic command-line tools. 
Follow the Android and iOS platform guides to install required platform dependencies.

### install ionic
after you're npm installed, use npm in your console to download ionic plugin by using this command
<div class="highlight"><pre>
npm install -g ionic
</pre></div>

### install cordova
then ,you need to install cordova plugin ,cordova plugin use to connect your code with native mobile like (camera,gps,etc)
<div class="highlight"><pre>
npm install -g cordova
</pre></div>

### choose your starter project
ionic have 3 stater template including blank,tabs,and side menu starter.and you can get the template using this command
<div class="highlight"><pre>
ionic start yourAppsName blank|tabs|sidemenu
</pre></div>      

## lets code 

###project structure
there is ionic project stucture
<div class='article-image'>
      <img src="/assets/images/get-start-ionic/project-structure.PNG"></img>

</div>

### 3 biggest component you should to know
<ul>
      <li>
            <h5>www</h5>
            <p>www is the place to put all your application code ,like layout(html+css),application logic (js)</p>
      </li>
       <li>
                  <h5>plugins</h5>
                  <p>if you want to add cool native feature like (GPS,maps,beacon,camera etc) in your ionic apps</p>
                  
                  <p>you can use this command</p>
                  <div class="highlight"><pre>
                        ionic plugin add pluginUrl 
                  </pre></div>
                  
       </li>
       <li>
             <h5>platforms</h5>
            <p>when you want to build your ionic apps ,to some platform like (android , ios ,or wp) ,you can generate native project structure version of your ionic application</p>
            <p>so you can open that in your native application IDE ex:(android studio or xcode) and you can build your apps</p>
            <p>to add platform in ionic you can use</p>
                         <div class="highlight"><pre>
                               ionic platform add (android|ios|wp) 
                         </pre></div>
                         <p>and then the project will generated in platforms project</p>
              </li>
</ul>

    