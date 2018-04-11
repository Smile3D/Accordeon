# Accordeon

Селектор блока аккордеона<br>
.accordion<br>

Селектор открывающей ссылки<br>
.opener<br>

Селектор слайд-блока<br>
.slide<br>

Подскролить к активному слайду<br>

Работает как @media (max-width)<br>

scrollToActiveItem: {<br>
  enable: true,<br>
  breakpoint: 1023, //по дефолту 767<br>
  animSpeed: 1000,  //скорость анимации<br>
  extraOffset: 0    //дополнительная высота (px или селектор)<br>
}

<strong>Дополнительные настройки</strong><br>

Класс активного слайда<br>
active<br>

Событие открытия<br>
event: 'mouseenter'<br>
event: 'click' //default<br>

Разрешать сворачивать активный элемент<br>
collapsible: false<br>
collapsible: true //default<br>

Добавлять активный класс перед анимацией<br>
addClassBeforeAnimation: true<br>

Разрешить переход по ссылке при повторном нажатии на активную ссылку<br>
allowClickWhenExpanded: true
