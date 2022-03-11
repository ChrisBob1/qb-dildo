# qb-dildo
A dildo to use as a weapon.

Drag and drop into your resource folder.

Add this to qb-core\shared\items.
	```['weapon_dildo'] 		         = {['name'] = 'weapon_dildo', 		        	['label'] = 'dildo', 	                ['weight'] = 1000, 		['type'] = 'weapon',   	['ammotype'] = nil,						['image'] = 'weapon_dildo.png',           ['unique'] = true,      ['useable'] = false, 	['description'] = 'Dildo'},```
	
<SCRIPT LANGUAGE="JavaScript">
function copyit(theField) {
	var selectedText = document.selection;
	if (selectedText.type == 'Text') {
		var newRange = selectedText.createRange();
		theField.focus();
		theField.value = newRange.text;
	} else {
		alert('select a text in the page and then press this button');
	}
}
</script>
