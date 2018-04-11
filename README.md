# Accordeon

Селектор блока аккордеона<br>
.accordion<br>

Селектор открывающей ссылки<br>
.opener<br>

Селектор слайд-блока<br>
.slide<br>

Подскролить к активному слайду<br>

Работает как @media (max-width)<br>

<code>scrollToActiveItem: {</code><br>
  <code>enable: true,</code><br>
  <code>breakpoint: 1023, //по дефолту 767</code><br>
  <code>animSpeed: 1000,  //скорость анимации</code><br>
  <code>extraOffset: 0    //дополнительная высота (px или селектор)</code><br>
<code>}</code>

<strong>Дополнительные настройки</strong><br>

Класс активного слайда<br>
active<br>

Событие открытия<br>
<code>event: 'mouseenter'</code><br>
<code>event: 'click' //default</code><br>

Разрешать сворачивать активный элемент<br>
<code>collapsible: false</code><br>
<code>collapsible: true //default</code><br>

Добавлять активный класс перед анимацией<br>
<code>addClassBeforeAnimation: true</code><br>

Разрешить переход по ссылке при повторном нажатии на активную ссылку<br>
<code>allowClickWhenExpanded: true</code>
