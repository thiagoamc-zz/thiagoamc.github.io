---
layout: post
title:  "CSS Viewport Unit"
date:   2015-07-29 
categories: css viewport unit
---

##vw
É a largura do viewport, supondo que estivemos usando um celular de medida 320px x 480px, 100vw seria equivalente a 100% da altura do viewport. Cada unidade do vw é equivalente a 1% de sua largura.

{% highlight ruby %}
.ex-vh {
	width: 100vw;
	height: 100vh;
}
{% endhighlight %}

<iframe id="cp_embed_jsFva" src="//codepen.io/snaptin/embed/NqEzrG?height=268&amp;theme-id=0&amp;slug-hash=jsFva&amp;default-tab=result&amp;user=snaptin" scrolling="no" frameborder="0" height="268" allowtransparency="true" allowfullscreen="true" class="cp_embed_iframe undefined" style="width: 100%; overflow: hidden;"></iframe>

###Exemplos viewport height
[Codepen](http://codepen.io/anon/pen/NqEzrG)

##vh

É a altura do viewport, supondo que estivemos usando um celular de medida 320px x 480px, 100vh seria equivalente a 100% da altura do viewport. Cada unidade do vh é equivalente a 1% de sua altura.

{% highlight ruby %}
.ex-vh {
	width: 100vw;
	height: 100vh;
}
{% endhighlight %}

###Exemplos viewport height

##vmin

É a menor das unidades utilizadas no viewport, supondo que temos um celular 320px x 480px, o vmin seria 320px onde 100vmin equivale aos 320px ou 100% do viewport.

{% highlight ruby %}
.ex-vmin {
	width: 100vw;
	height: 10vmin;
}
{% endhighlight %}

##vmax

É a maior das unidades utilizadas no viewport, supondo que temos um celular 320px x 480px, o vmax seria 480px onde 100vamx equivale aos 480px ou 100% do viewport.

{% highlight ruby %}
.ex-vmax {
	width: 100vw;
	height: 10vmax;
}
{% endhighlight %}

##Suporte Navegadores:
No IE9 apenas as unidades vmin 
IE 10+, Firefox 19+, Chrome 26+, Safari 7+, Opera 15+, Android 4.4+, iOS 6+
Mais detalhes sobre suporte acesse [caniuse][caniuse] 

##Referências:
Documentação W3C [W3C Module Level 3][w3cmodlvl3]

[caniuse]:    http://caniuse.com/#feat=viewport-units
[w3cmodlvl3]: https://drafts.csswg.org/css-values-3/