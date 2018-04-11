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

Дополнительные настройки

Класс активного слайда
1. active

Событие открытия

1. event: 'mouseenter'
2. event: 'click' //default

Разрешать сворачивать активный элемент

1. collapsible: false
2. collapsible: true //default

Добавлять активный класс перед анимацией

1. addClassBeforeAnimation: true

Разрешить переход по ссылке при повторном нажатии на активную ссылку

1. allowClickWhenExpanded: true
