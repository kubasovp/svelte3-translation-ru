---
title: Стили
---

Как и в обычном HTML, в компоненте можно использовать тег `<style>`. Давайте добавим несколько стилей к элементу `<p>`:

```html
<style>
	p {
		color: purple;
		font-family: 'Comic Sans MS';
		font-size: 2em;
	}
</style>

<p>Просто строка текста</p>
```

Важно отметить, что эти стили *изолируются в компоненте*. Вы не сможете случайно затереть стили элементов `<p>` из других частей вашего приложения. Мы сможем в этом убедиться в следующем уроке.