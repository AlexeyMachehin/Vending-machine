## Вендинговый аппарат

Ссылка на netlify.com: [Vending-machine](https://renue-vending-machine.netlify.app)

***

## Описание:
* В проекте используется библиотека react
* Имитация вендингового аппарата. Количество товаров, купюр для сдачи находятся в моковых данных.
При отсутствии купюр аппарат выдает сдачу товаром. Если нет ни купюр, ни товара для сдачи - показывается сообщение:
"Извините, нет сдачи, позвоните по номеру: 88005677453 и мы вернем вам "сумма" руб."

***

## Стек технологий: 
* React 
* Vite
* Material UI
* Eslint
* Stylelint
* Fullscreen API
 

***

## Команды:
* Старт проекта: npm run preview
* Сборка проекта: npm run build
* Старт режима разработчика: npm run dev
* stylelint: npm run stylelint
* eslint: npm run eslint

***

## Техническое задание:
* Необходимо реализовать имитацию вендингового аппарата. Дизайн аппарата
полностью на ваше усмотрению. В техническом задании описаны не все моменты,
часть вещей нужно додумать самостоятельно и доработать в решении. 

* Аппарат должен:
1. Принимать деньги номиналом в 50, 100, 500 и 1000 рублей.
2. Выдавать сдачу номиналом в 1, 5, 10, 50, 100 и 500 рублей.
(количество каждого номинала можно задать как случайном образом,
так и с помощью мока).
2.1 Если сдачи нет, то выдать товар на сумму недостающей сдачи.
3. Иметь 8 разных видов товара (название и цена на ваше усмотрение).
3.1 Если товара нет в наличии, визуально отобразить это.
4. Выдавать товар сразу после его выбора.
5. Выдавать сдачу по отдельной кнопке.

***

Превью:
![image](https://user-images.githubusercontent.com/99137228/218194305-e958ce35-edcd-4d21-949c-94944000cb1d.png)

