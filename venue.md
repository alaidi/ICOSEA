---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

# Conference Venue

The conference will be held from 29 30  November 2017 at the College of Engineering, Wasit University , located in the heart of the city center and 2-hours from Baghdad International Airport. 

<div class="row">
<h1>Bootstrap 3 Lightbox image gallery using Modal</h1>

<div class="col-lg-3 col-sm-4 col-xs-6"><a title="Image 1" href="#"><img class="thumbnail img-responsive" src="//placehold.it/600x350"></a></div>


<hr>

<hr>
</div>
</div>
<div tabindex="-1" class="modal fade" id="myModal" role="dialog">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<button class="close" type="button" data-dismiss="modal">×</button>
<h3 class="modal-title">Heading</h3>
</div>
<div class="modal-body">

</div>
<div class="modal-footer">
<button class="btn btn-default" data-dismiss="modal">Close</button>
</div>
</div>
</div>
<script type="text/javascript">
$(document).ready(function() {
$('.thumbnail').click(function(){
$('.modal-body').empty();
var title = $(this).parent('a').attr("title");
$('.modal-title').html(title);
$($(this).parents('div').html()).appendTo('.modal-body');
$('#myModal').modal({show:true});
});
});
</script>
