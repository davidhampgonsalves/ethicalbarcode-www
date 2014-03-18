to change the css you have to
	1. makes changes
	2. recompile/compress the less: lessc --yui-compress styles.less > styles.css
	3. add styles.css content to index.html

 >> 4. also add mobile.css to index.html after the other styles because of the ie conditional comments that break less