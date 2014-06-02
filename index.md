template_url:  https://github.com/jgenso/template-base
## Welcome

Welcome to your new Telegram site.  Check out the [Getting Started](/getting_started) page
for information on how to set up your site.

<div id="content">
                  <div class="row">    
		    <div class="col-md-12"> 
		      
		      <div class="panel">
			<div class="panel-body" data-lift="blog.posts?max=15">
		
			  
			  <!--/stories-->          
			  <div class="row" data-post="item">    
			    <br>
			    <div class="col-md-2 col-sm-3 text-center">
			      <a class="story-img"  href="#"><img src="//placehold.it/100" style="width:100px;height:100px" class="img-circle"></a>
			    </div>
			    <div class="col-md-10 col-sm-9">
			      <h3><a data-post="link" href="#">Blog Post</a></h3>
			      <div class="row">
				<div class="col-xs-9">
				  <p data-post="shortcontent">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis pharetra varius quam sit amet vulputate. 
				  Quisque mauris augue, molestie tincidunt condimentum vitae, gravida a libero. Aenean sit amet felis 
				  dolor, in sagittis nisi. Sed ac orci quis tortor imperdiet venenatis. Duis elementum auctor accumsan. 
				  Aliquam in felis sit amet augue.</p>
				  <p class="lead" data-post="more"><a href="# class="btn btn-default">Read More</a></p>
				  <p class="pull-right"><span class="label label-default" data-lift="htag-list">keyword</span></p>
				  <ul class="list-inline"><li><span data-post="date">2012/12/14</span></li><li><a href="#"><i class="glyphicon glyphicon-comment"></i> 0 Comments</a></li><<!--li><a href="#"><i class="glyphicon glyphicon-share"></i> 34 Shares</a>--></li></ul>
				  </div>
				<div class="col-xs-3"></div>
			      </div>
			      <br><br>
			    </div>
			  </div>
			  <hr>
			  <!--/stories-->
			  
			  
			  <!--<a href="/" class="btn btn-primary pull-right btnNext">More <i class="glyphicon glyphicon-chevron-right"></i></a>-->
		
			  
			</div>
		      </div>
				                                                                       
					                                
				                                      
		   	</div><!--/col-12-->
		  </div>
                </div>

<span data-lift="if?extra_true=has_blog">Welcome to my blog.  Here are my most recent blog posts:</span>

<div data-lift="if?extra_true=has_blog">
      <div data-lift="blog.simple"></div>
</div>

[title: Home]: /
