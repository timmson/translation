---
layout: mechanics
title: Почему LeSS?
order: 10
---

<iframe width="560" height="315"
src="https://www.youtube.com/embed/cvz4364pC0g" frameborder="0"
allowfullscreen></iframe>

Традиционная водопадная модель разработки устарела. Она работает плохо, независимо от того говорим мы о разработке небольших или наоборот крупных продуктов. Начиная с 2001 года, Agile-разработка и Scrum в частности, произвели революцию в разработке программного обеспечения. Но когда возникает вопрос - как применять Agile-разработку в больших группах, многие люди говорят “не стоит” или “работайте только с небольшой командой” или “используйте Скрам только на уровне одной команды". Пользы в этих советах, конечно, мало. И не смотря на то, что лучше избегать увеличения количества людей вовлеченных в разработку, также очевидно и то, что крупномасштабная разработка продуктов никуда не исчезнет. Поэтому приходится искать подходы к тому, как сделать ее лучше.
Мы, Крэг Ларман (Craig Larman) и Бас Водди (Bas Vodde) в разном качестве долгое время занимались разработкой программного обеспечения в традиционной последовательной модели, Unified Process, CMMi и других. И ни один из этих подходов не выглядел правильным. При этом Скрам, с другой стороны, хорошо себя зарекомендовал для однокомандной разработки. В результате возник вопрос - «Как мы можем масштабировать Скрам, не потеряв его сильные качества?»

## LeSS это масштабируемый Скрам

В чем сила Скрама? На этот вопрос не так-то просто ответить. Безусловно, концепции и принципы, лежащие в основе Скрама, такие как [Прозрачность](../principles/transparency.html), [Эмпирический процесс контроля](../principles/empirical-process-control), Итеративная разработка и [Самоорганизованные команды](../management/self_managing_teams.html) имеют решающее значение. Однако эти принципы существуют уже довольно давно, поэтому их включение в Скрам не объясняет его успеха. После долгих обсуждений, мы пришли к выводу:

Успех Скрама в удачном сочетании общих принципов и конкретных практик.
{: .box_top_bottom  .text_centered_bold }

Таким образом, чтобы сохранить [масштабируемый Скрам как Скрам](../principles/large_scale_scrum_is_scrum.html), нам необходимо найти аналогичный баланс, чтобы мы могли сказать:

Для больших групп успех LeSS в удачном балансе между конкретными элементами и эмпирическим процессом управления.
{: .box_top_bottom  .text_centered_bold }

Это приводит к некоторым решениям:

* LeSS  должен быть простым
При масштабировании, существует тенденция добавления ролей, артефактов, процессов и т. д. Этого нужно избегать, чтобы процесс эмпирически создавался продуктовой группой. Большинство других масштабируемых фреймворков попадают в ловушку обеспечения определенного процесса. В LeSS мы хотим избежать этой ловушки.
* LeSS - это Масштабируемый Скрам
Вместо простого использования Скрама в качестве строительного блока для масштабируемого фреймворка, нам требуется посмотреть на Скрам и для каждого его элемента спросить: "Почему он там?”, а затем -  ”Если у нас есть больше одной команды, как мы можем применять его с таким же успехом на больших масштабах?”
* Масштабируемый вместо подогнанного
Общей концепцией развития процессов является описание универсального, общего фреймворка, а затем его контекстная подгонка. Это плохо работает, потому что люди зачастую предполагают, что в их контексте нужно все. Это предположение часто приводит к созданию раздутых процессов. LeSS сводит все это к минимуму. Мы признаем, что масштабирование может потребовать «большего» (количества элементов, правил, артефактов фреймворка и т.п.), но вместо "замусоривания" LeSS опциональными элементами мы создали отдельный фреймворк -  [LeSS Huge](../less-huge/index.html).

## Обзор LeSS

То, как мы видим LeSS очень хорошо изображено на рисунке:

<div>
  {% figure "/img/framework/less-complete-picture", "Large Scale Scrum (Less) Overview" %}
</div>

## LeSS использует эксперименты

В наших первых книгах, [Scaling Agile and Lean Development](http://www.amazon.com/Scaling-Lean-Agile-Development-Organizational/dp/0321480961) и [Practices for Scaling Agile and Lean Development](http://www.amazon.com/Practices-Scaling-Lean-Agile-Development/dp/0321636406), мы определили масштабируемый Скрам как набор экспериментов, исходя из принципа:

Не существует «лучших практик». Есть только практики, которые хороши в конкретном контексте.
{: .box_top_bottom  .text_centered_bold }

Поэтому в книгах описано много экспериментов, которые мы провели. Некоторые их них мы рекомендуем вам попробовать, некоторые рекомендуем избегать, часть будут работать в определенных контекстах, но при этом будут иметь плохие последствия в других. Такой подход действительно работает и мы получили массу положительной обратной связи. 

Но мы также получили обратную связь от людей, которые были немного обескуражены таким подходом. Им требовалось что-то большее, чего можно было бы придерживаться ... что-то менее зависимое от контекста ... некоторые правила. Основываясь на этой обратной связи, мы подумали и вернулись к модели обучения Shu Ha Ri:

<figure>
  <img src="/img/framework/shuhari.png" alt="shuhari.png">
</figure>

Эта модель показывает различные этапы, которые учащиеся проходят при изучении новых концепций:

* Shu---следуй правилам для изучения основ
* Ha---нарушай правила и исследуй контекст
* Ri---овладей в совершенстве и найди свой собственный путь

Мы поняли, что наши предыдущие работы по масштабированию не обеспечивали поддержки на уровне Shu, что вызывало трудности и путаницу у людей, которые только начинали изучать гибкую разработку в крупных продуктовых группах. Это стало еще более очевидным, когда другие, более предиктивные подходы к масштабированию начали предлагать советы начального уровня. Следовательно ...

## LeSS это фреймворк

LeSS - это больше чем набор принципов и экспериментов. Он также предоставляет фреймворк с правилами. Правила LeSS определяют, что такое LeSS (а что нет) и они предоставляют конкретный фреймворк для применения LeSS. В LeSS фреймворке продуктовые группы могут проводить эксперименты и определять, что лучше всего подходит для них в данный момент.

Это также лежит в основе третьей книги LeSS, просто названной [Large-Scale Scrum](http://www.amazon.com/Large-Scale-Scrum-More-Craig-Larman/dp/0321985710). В этой книге LeSS определяется как:

* правила LeSS, которые обеспечивают LeSS фреймворк (и LeSS Huge фреймворк для более крупных продуктовых групп)
* Руководства для применения LeSS
* Эксперименты из двух первых двух книг.

Таким образом, LeSS прост и остается верным духу Scrum. В то же время, как и Scrum, LeSS предоставляет достаточно конкретных практик для старта и достаточную гибкость и мощность для масштабирования.

Перевод статьи осуществлен [Сергеем Господчиковым](https://less.works/ru/profiles/sergey-gospodchikov) и [Алексеем Ворониным](https://facebook.com/agileinjection)