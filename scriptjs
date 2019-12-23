$(function(){
    scrollfadeon("#commitment");
    scrollfadeon("img");
    scrollfadeon(".btn");
    


        
    function scrollfadeon(id){
        $(window).scroll(function (){
            $(id).each(function(){
              var imgPos = $(this).offset().top;
              var scroll = $(window).scrollTop();
              var windowHeight = $(window).height();
            //   if (scroll > imgPos - windowHeight + windowHeight/5){
              if (scroll > imgPos - windowHeight*4/5){
                $(this).addClass("fade_on");
                $(this).removeClass("fade_off");
              } else {
                $(this).removeClass("fade_on");
                $(this).addClass("fade_off");
              }
            });
        });
    }
        
});
