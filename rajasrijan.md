---
redirect_from: 
   - /rajasrijan
   - /rajasrijan/
layout: page
title: Portfolio
tagline: Projects, Tools & Skills
---
{% include JB/setup %}

<div class="container">
  <div class="row">
    <div class="col-xs-12 col-md-6">
      <div class="row">
        <div class="col-xs-6">
          <img class="img-responsive img-circle"
               src="https://avatars2.githubusercontent.com/u/9075044"
               alt="Srijan Kumar Sharma Profile Image"/>
        </div>
        <div class="col-xs-6">
          <p>
                My skills include c++, c, assembly, Python, OpenCV, TensorFlow, ..blah ..blah... I'm a machine learning enthusiast. In my free time, I enjoy reading publications relating to Machine Learning and Computer Vision. I love playing computer games, particularly League of Legends.
          </p>
        </div>
      </div>
    </div>
    
    <div class="col-xs-12 col-md-6">
      <div class="list-group">
        <h3 class="tab">goodies to browse</h3>
        {% for post in site.posts %}
          <a href="{{ BASE_PATH }}{{ post.url }}" class="list-group-item">
            <h4 class="list-group-item-heading">{{ post.title }}</h4>
            <p class="list-group-item-text">
              <span>{{ post.date | date_to_string }}</span> &raquo; 
              {{ post.description }}
            </p>
          </a>
        {% endfor %}    
      </div>
    </div>
  </div>
</div>

### Thank You

Browse my [Github](https://github.com/rajasrijan) repositories .. 
Check out my [Linkedin](https://in.linkedin.com/in/srijan-kumar-sharma-0a9659b4) profile .. 
