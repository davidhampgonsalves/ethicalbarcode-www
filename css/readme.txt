to change the css you have to
	1. makes changes
	2. recompile/compress the less:
		lessc --yui-compress css/styles-bellow.less  > css/styles-bellow.css
		lessc --yui-compress css/styles-above.less  > css/styles-above.css
	3. copy above content to index.html head
	4. subpages still use styles.css rather then above/bellow versions