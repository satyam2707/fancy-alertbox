----------------------
    INTRUCTIONS
----------------------

1.USING STATIC CONTENT
  
  Please follow the below steps to use alert box as a static content
  (a) Create a div which contain the data you want to show in alert box.
  (b) Assign a id to your container.
  (c) Write the following JQuery code to show popup

      $(document).ready(function()
       {
	 $('#alert').alerbox({
			      div:'#content'
	                    });
	
    
        });

        #alert :-> ID of the element which will be clicked and alert box will be open.
        #content :-> ID of the element which you want to put in alert box.
                    This element should be by default hidden.


2.LOAD CONTENT USING AJAX
   
   Please follow the below steps to load data in alertbox using ajax url
  
  (a) Write the following JQuery code to show popup

      $(document).ready(function()
       {
	 $('#alert').alerbox({
			      url:'index.html'
	                    });
	
    
        });
       
        #alert :-> ID of the element which will be clicked and alert box will be open.
        url:-> Url of the page which contains the data which will be put in the alertbox
  

