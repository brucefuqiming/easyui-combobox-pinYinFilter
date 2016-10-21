# easyui-combobox-pinYinFilter
**easyui combobox中文拼音检索插件**

## Resources

* [jQuery EasyUI](http://www.jeasyui.com/)

## Installing

```html
<script src="comboboxPinYin.js"></script>
```
```html
  <input class="easyui-combobox" 
			name="language"
			data-options="
					url:'combobox_data.json',
					filter:filterPinYin,
					method:'get',
					valueField:'value',
					textField:'text',
					multiple:false,
					panelHeight:'auto'
			">
```

```html
  <input id="jsCombobox" />
	<script type="text/javascript">
	    $('#jsCombobox').combobox({
			url:'combobox_data.json',
			valueField:'value',
			textField:'text',
			filter:filterPinYin
        });
	</script>
```
