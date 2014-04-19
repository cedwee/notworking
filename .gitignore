API.chatLog(" Lazy Room Script running :ballot_box_with_check: version dickhil/cedick ", true);
function initEnvironment(){
       if (plugCubed === undefined) {
        //$.getScript('http://alpha.plugCubed.net/plugCubed.js'); 
        //$.getScript('https://d1rfegul30378.cloudfront.net/alpha/plugCubed.js');
        $.getScript('https://d1rfegul30378.cloudfront.net/files/plugCubed.js');
        };
}
initEnvironment();
var plugCubed,
RMEnhancedModel = require('f5884/a365f/b5948').extend({
    init: function(){
        setTimeout($.proxy(this.initCSS,this), 1500);
        this.proxy = {
            onChat: $.proxy(this.onChat, this)
        };
        API.on(API.CHAT,this.proxy.onChat);
        String.prototype.equalsIgnoreCase = function(other) {
        return this.toLowerCase() === other.toLowerCase();
        };
    },
    initCSS: function() {
                //$("body").prepend('<img src="http://i.imgur.com/u94c2tZ.gif" id="LAZY">');
                //$("body").prepend('<style> #lazy { position:absolute; top: 40px; left: 30px; } </style>');
                $(".background").find('img').attr('src',' http://i.imgur.com/XSRJtd9.png ');
        $('head').append('<link rel="stylesheet" type="text/css" href="https://dl.dropboxusercontent.com/s/x5xi4mi3aruk1w9/style.css">');
                $('body').append('<div id="tooltip_custom" class="right" style="top: 28px; right: 120px; visibility: hidden;"><span>AutoWoot Enable/Disable</span><div class="corner"></div></div>');
                $('body').append('<div id="tooltip_custom1" class="right" style="top: 28px; right: 70px; visibility: hidden;"><span>AutoJoin Enable/Disable</span><div class="corner"></div></div>');
                $('#room').find('canvas').filter(function() { return $(this).css('opacity') < 1; }).remove();
                $('#room').append('<div class="is-leave" style="margin-top: 10px; text-align: center;"></div>');
               // $('#room').append('<div class="is-leave" style="margin-top: 300px; text-align: center;"><a href="https://www.facebook.com/groups/547885508611462/" target="_blank"><img src="http://i.imgur.com/F1p1ZET.png"></a></div>');
                //$('#dj-booth').append('<div id="rmbooth" style="background-image: url(http://i.imgur.com/tg0qpxC.png);"></div>');
                $('#chat-header').append('<div id="autowoot-button" class="chat-header-button" onMouseOver="show(\'tooltip_custom\')" onMouseOut="hide(\'tooltip_custom\')" onClick="woot()"><i class="icon icon-autowoot-off"></i></div>');
    },
    onChat: function(data){
    },
});
var RMEnhanced = new RMEnhancedModel();
