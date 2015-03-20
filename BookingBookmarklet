javascript:(function(){ 
	var items = document.querySelectorAll(".fc-event-title");
    var d=window.open('','BookingSheetGenerator','status=no,directories=no,location=no,resizable=no,menubar=no,width=841,height=595,toolbar=no');
    d.document.open();
    d.document.write("
	    <object width=841 height=595 data='http://www.martin-rowe.co.uk/Tonmeister/BookingSheet.pdf' type='application/pdf'>
	    	<embed width=841 height=595 src='http://www.martin-rowe.co.uk/Tonmeister/BookingSheet.pdf' type='application/pdf' />
		</object>
	");
    d.document.write("
    	<div style='position:absolute; top:195px; left:100px; font-size:11px; line-height:1.1'>
    ");
    for(var i=0;i<items.length;i++){
		d.document.write(items[i].innerHTML + "<br />");
	};
	d.document.write("
		</div><div style='position:absolute; top:195px; left:640px; font-size:11px; line-height:1.1'>
	");
    for(var i=0;i<items.length;i++){
		d.document.write(items[i].innerHTML + "<br />");
	};
    d.document.close();
 })();