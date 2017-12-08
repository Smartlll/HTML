># `<!DOCTYPE>`标签 #

- HTML文档中使用该标签，可以提前告知浏览器文档类型；
- 在HTML4.01中，该标签声明需引用`DTD`（文档类型声明），因为HTML4.01是基于SGML（Standard Generalized Markup Language 标准通用标记语言）的；`DTD`制定了标记语言的规则，确保浏览器能正常的渲染内容；
- 在HTML5中，该标签的声明不要求引用`DTD`，因为HTML5不是基于SGML的；
- HTML 4.01中，该标签的声明有三种分别为：`Strict`、`Transitional`、`Frameset`，而HTML5中只有一种形式：`html`；
- 该标签<strong>没有结束标签</strong>，声明不区分大小写；

># 常见的`<!DOCTYPE>`声明 #

- **HTML5**
		<!DOCTYPE html>
- **HTML 4.01 Strict**
	这个`DTD`包含所有的HTML元素和属性，但<strong>不包括</strong>表象或过时的元素(如`font`)。框架集是不允许的。
		<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">  <!-- strict 严格的  精确的 -->
- **HTML 4.01 Transitional**
	这个`DTD`包含所有的HTML元素和属性，<strong>包括</strong>表象或过时的元素（如：`font`）。框架集是不允许的。
		<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">  <!-- loose 自由的  散漫的 -->
- **HTML 4.01 Frameset**
	这个DTD与HTML 4.01 Transitional相同，但是允许使用框架集内容
		<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">