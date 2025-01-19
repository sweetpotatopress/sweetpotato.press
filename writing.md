---

layout: page
title: writings

---
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 50%;
  padding: 5px;
}

.row::after {
  content: "";
  clear: both;
  display: table;
} 
@media screen and (max-width: 500px) {
  .column {
    width: 100%;
  }
}
</style>

<div class="column">
<h2></h2>

 <div class="row">
  <div class="column">
  writings
  <br>
  <br>
   <main class="parent">
    {% for post in site.posts %}
        <div>
            <div class="pd">{{ post.date | date: "%m/%Y" }}</div> 
            <a href="{{ post.url }}">
                {{ post.title }}
            </a>
        </div>
    {% endfor %}
</main>
<br>
<br>
</div>

<p>

</p>
</div> 

