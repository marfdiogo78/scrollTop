# scrollTop
ScrollTop com classe


var target = $('.form_msg');
var $target = $(target);
$('html, body').stop().animate({
    'scrollTop': $target.offset().top-60
}, 800, 'swing');

ScrollDown
var info = $(".regulament-info");
$('html, body').animate({ scrollTop: info.offset().top }, 1000);
