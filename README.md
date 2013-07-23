##Informerly Button

HTML buttons for third party sites. 


#####Option 1 - Button Tag (may not render correctly for IE8)
```html
<a href="http://informerly.com" target="_blank" style="padding-bottom: 5px;" title="Informerly">
	<button type="button">
		<img src="http://i.imgur.com/42bU6uL.png" alt="Informerly" style="padding: 2px 1px 1px 1px;">
	</button>
</a>
```

#####Option 2 - Style Link (no hover/click styling)
```html
<a href="http://informerly.com" target="_blank" title="Informerly">
	<img src="http://i.imgur.com/42bU6uL.png" alt="Informerly" style="text-decoration: none; background-color: #EEEEEE; color: #333333; padding: 4px; border: 1px solid #CCCCCC; -moz-border-radius: 4px; border-radius: 4px;">
</a>
```