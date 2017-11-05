$(document).ready(function(){
	var serviceItem = $('.servece__item');
	for (var i = 0; i <= 32; i++) {
		serviceItem.clone().appendTo('.content__servece');
	}
});