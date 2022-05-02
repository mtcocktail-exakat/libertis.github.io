---
layout: default
permalink: /membres/
---

## Membre Libertis

<div class="row">
  {% for membre in site.data.membres %}
    <div class="col-md-4 mb-5">
      <div class="card border-0 shadow h-100">
        <img class="card-img-top" src="{{ item.logo }}" alt="" />
        <div class="card-body">
          <h4 class="card-title">{{
            item.title
          }}</h4>
          <p class="card-text">
            {{
            item.description
          }}
          </p>
        </div>
        <div class="card-footer">
          <a href="{{ item.link }}" class="btn btn-primary" target='_blank'>En savoir plus >></a>
        </div>
      </div>
    </div>
  {% endfor %}
  <div class="col-md-4 mb-5">
    <div class="card border-0 shadow h-100">
      <img class="card-img-top" src="http://placeholder.pics/svg/400x300/3cb371-3cb371/3cb371-3cb371" alt="" />
      <div class="card-body">
        <h4 class="card-title">Card title</h4>
        <p class="card-text">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sapiente
          esse necessitatibus neque sequi doloribus.
        </p>
      </div>
      <div class="card-footer">
        <a href="#" class="btn btn-primary">Find Out More!</a>
      </div>
    </div>
  </div>
  
</div>
<!-- /.row -->