# baguette-photo-gallery

One of the biggest tricks to successful mobile design is ensuring that your navigation remains functional and user-friendly even if the design changes.


  		  
## Tutorial		  
For detailed instruction's, view Solodev's [Converting Horizontal Navigation into Mobile Dropdown Menus](https://www.solodev.com/blog/web-design/converting-horizontal-navigation-into-mobile-dropdown-menus.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/v841y4he/).

## HTML

The tutorial contains the following basic HTML markup.

```
<div class="sectional-nav clearBoth">
	<div class="container">
	  <ul class="hidden-sm-down p-0 d-flex align-items-center justify-content-between">
		<li><a href="https://www.solodev.com/pricing/">Pricing</a></li>
		<li><a href="https://www.solodev.com/product/create.stml">Product</a></li>
		<li><a href="https://www.solodev.com/resources/">Resources</a></li>
		<li><a href="https://www.solodev.com/customers/">Customersy</a></li>
		<li><a href="https://www.solodev.com/blog/">Blog</a></li>
	  </ul> 
	</div>
	<select name="sectional_nav" id="sectional_nav" class="form-control hidden-md-up" onchange="window.location.href=this.value">
	  <option value="0">Navigate to...</option>
	  <option value="https://www.solodev.com/pricing/">Pricing</option>
	  <option value="https://www.solodev.com/product/create.stml">Product</option>
	  <option value="https://www.solodev.com/resources/">Resources</option>
	  <option value="https://www.solodev.com/customers/">Customers</option>
	  <option value="https://www.solodev.com/blog/">Blog</option>
	</select>
</div>

```

## CSS

All required CSS is contained with horizontal-nav-mobile.css


## External Resources

This tutorial includes the following third party resources.

```
<link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/tether/1.4.0/js/tether.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>
```

