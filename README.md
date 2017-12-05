# add Loader


# link css to page
    <link rel="stylesheet" href="<?php echo base_url('assets/template/');?>css-loader.css">

# add this html into page
    <div id="siteloader" class="loader loader-default " data-text></div>



  $('#siteloader').addClass('is-active');
  
  $('#siteloader').removeClass('is-active');
  
  $(document).ajaxStop(function() {
      $('#siteloader').removeClass('is-active');
  });
