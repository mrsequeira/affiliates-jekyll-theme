---
layout: page
title: Websites that I haved cooked
comments: true
---

<style>  
  .card:hover {
      box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
  }
  
  imgn {
      border-radius: 5px 5px 0 0;
  }
  
  .containern {
      padding: 2px 16px;
  }
  section.pricing {
  background: #9CECFB;
  /* fallback for old browsers */
  background: -webkit-linear-gradient(to right, #0052D4, #65C7F7, #9CECFB);
  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to right, #0052D4, #65C7F7, #9CECFB);
  /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
}

.pricing .card {
  border: none;
  border-radius: 1rem;
  transition: all 0.2s;
  box-shadow: 0 0.5rem 1rem 0 rgba(0, 0, 0, 0.1);
}

.pricing hr {
  margin: 1.5rem 0;
}

.pricing .card-title {
  margin: 0.5rem 0;
  font-size: 0.9rem;
  letter-spacing: .1rem;
  font-weight: bold;
}

.pricing .card-price {
  font-size: 3rem;
  margin: 0;
}

.pricing .card-price .period {
  font-size: 0.8rem;
}

.pricing ul li {
  margin-bottom: 1rem;
}

.pricing .text-muted {
  opacity: 0.7;
}

.pricing .btn {
  font-size: 80%;
  border-radius: 5rem;
  letter-spacing: .1rem;
  font-weight: bold;
  padding: 1rem;
  opacity: 0.7;
  transition: all 0.2s;
}

/* Hover Effects on Card */

@media (min-width: 992px) {
  .pricing .card:hover {
    margin-top: -.25rem;
    margin-bottom: .25rem;
    box-shadow: 0 0.5rem 1rem 0 rgba(0, 0, 0, 0.3);
  }
  .pricing .card:hover .btn {
    opacity: 1;
  }
}
@import url('https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css');
section{
	padding: 60px 0;
}
section .section-title{
	text-align:center;
  color:#007CC5;
	margin-bottom:50px;
	text-transform:uppercase;
}
#what-we-do{
	background:#ffffff;
}
#what-we-do .card{
	padding: 1rem!important;
	border: none;
	margin-bottom:1rem;
	-webkit-transition: .5s all ease;
	-moz-transition: .5s all ease;
	transition: .5s all ease;
}
#what-we-do .card:hover{
	-webkit-box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
	-moz-box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
	box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
}
#what-we-do .card .card-block{
	padding-left: 50px;
    position: relative;
}
#what-we-do .card .card-block a{
	color:#007CC5 !important;
	font-weight:700;
	text-decoration:none;
}
#what-we-do .card .card-block a i{
	display:none;
	
}
#what-we-do .card:hover .card-block a i{
	display:inline-block;
	font-weight:700;
	
}
#what-we-do .card .card-block:before{
	font-family: FontAwesome;
    position: absolute;
    font-size: 39px;
    color:#007CC5;
    left: 0;
	-webkit-transition: -webkit-transform .2s ease-in-out;
    transition:transform .2s ease-in-out;
}
#what-we-do .card .block-1:before{
    content: "\f0b2";
}
#what-we-do .card .block-2:before{
    content: "\f0eb";
}
#what-we-do .card .block-3:before{
    content: "\f00c";
}
#what-we-do .card .block-4:before{
    content: "\f06e";
}
#what-we-do .card .block-5:before{
    content: "\f0c2";
}
#what-we-do .card .block-6:before{
    content: "\f15c";
}
#what-we-do .card:hover .card-block:before{
	-webkit-transform: rotate(360deg);
	transform: rotate(360deg);	
	-webkit-transition: .5s all ease;
	-moz-transition: .5s all ease;
	transition: .5s all ease;
}
</style>

<!-- <div class="col-md-6 grid-item">
<div class="card">
    <a href="{{ post.url | absolute_url }}">
        {% if post.image %} <img class="img-fluid" src="{{ site.baseurl }}/{{ post.image }}" alt="{{ post.title }}"> {% endif %}
    </a>
    <div class="card-block">
        <h2 class="card-title"><a href="{{ post.url | absolute_url }}">{{ post.title }}</a></h2>
        <h4 class="card-text">{{ post.excerpt | strip_html | truncatewords:30 }}</h4>
        <div class="metafooter">
            <div class="wrapfooter">
                {% if post.author %}
                <span class="meta-footer-thumb">
                <img class="author-thumb" src="https://www.gravatar.com/avatar/{{ author.gravatar }}?s=250&d=mm&r=x" alt="{{ author.display_name }}">
                </span>                
                <span class="author-meta">
                <span class="post-name"><a target="_blank" href="{{ author.web }}">{{ author.display_name }}</a></span><br/>
                {% endif %}
                <span class="post-date">{{ post.date | date_to_string }}</span>
                </span>
                <span class="post-read-more"><a href="{{ post.url | absolute_url }}" title="Read Story"><i class="fa fa-link"></i></a></span>
                <div class="clearfix"></div>
            </div>
        </div>
    </div>
</div>
</div> -->

<div class="masonrygrid row listrecent">
  <div class="container">

    <div class="row">
      <a href="https://teia19.pt" style="text-decoration:none"> 
        <div class="col-md-6 grid-item">
          <div class="card">
            <div class="containern text-center">
                <img src="https://teia19.pt/assets/images/teia19.png"  style="width:70% " >
                <h4><b>Teia 19</b></h4>
                <h8>Website, criado durante a época do Corona virus, para ajudar artistas que viram os seus eventos cancelados.</h8> 
            </div>
          </div>
        </div>
      </a>
        <div class="col-md-6 grid-item">
          <a href="https://zeus-sec.herokuapp.com/" style="text-decoration:none"> 
          <div class="card">
            <div class="containern text-center">
                <img src="https://zeus-sec.herokuapp.com/static/img/favicon.png"  style="width:70% " >
                <h4><b>ZEUS</b></h4>
                <h8>Website criado para o projeto final de Licenciatura Informática para monitorizar e manter segurança de máquinas.</h8> 
            </div>
          </div>
        </div>
      </a>

  </div>
</div> 

<!-- colocar aqui secao de projetos que posso vir a fazer -->
