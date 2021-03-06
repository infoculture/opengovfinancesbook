---
description: Сведения о субсидиях и субвенциях.
---

# Соглашения \(субсидии и субвенции\)

## Определение

Соглашения \(субсидии и субвенции\) - это форма предоставления бюджетных средств включающая следующие виды договоров:

* Соглашения \(договоры\), заключенные главными распорядителями средств федерального бюджета, а также нормативные правовые акты о предоставлении из федерального бюджета
* Соглашения \(договоры\), заключенные между некоммерческими организациями \(не являющимся федеральными государственными учреждениями\), получившими субсидию из федерального бюджета, и третьими лицами о предоставлении
* Соглашения, заключенные главными распорядителями, а так же нормативные правовые акты о предоставлении бюджетам субъектов Российской Федерации

{% hint style="info" %}
Например, Федеральное дорожное агентство предоставляет субсидию на 53,6 миллиардов рублей компании ООО "РТИТС" в рамках концессионного соглашения в отношении объектов, предназначенных для взимания платы в счет возмещения вреда, причиняемого автомобильным дорогам общего пользования федерального значения транспортными средствами, имеющими разрешенную максимальную массу свыше 12 тонн. Основанием является концессионное соглашение подписанное между организациями. 
{% endhint %}

## Структура

Сведения о субсидиях имеют сложную иерархическую структуру и включает:

* реквизиты организации распределяющей субсидии;
* реквизиты организации получателя субсидии;
* сведения о суммах, целях и кодах бюджетных классификаций;
* сведения о перечислении средств
* сведения о доп. соглашениях
* документы

{% file src="../../.gitbook/assets/7710568760-fedbudgetagreementapi.docx" caption="Описание схемы структуры данных реестра соглашений о субсидиях" %}

## Примеры

![&#x41F;&#x440;&#x438;&#x43C;&#x435;&#x440; &#x434;&#x43E;&#x43A;&#x443;&#x43C;&#x435;&#x43D;&#x442;&#x430; &#x441;&#x443;&#x431;&#x441;&#x438;&#x434;&#x438;&#x438; &#x421;&#x438;&#x431;&#x438;&#x440;&#x441;&#x43A;&#x43E;&#x43C;&#x443; &#x444;&#x435;&#x434;&#x435;&#x440;&#x430;&#x43B;&#x44C;&#x43D;&#x43E;&#x43C;&#x443; &#x443;&#x43D;&#x438;&#x432;&#x435;&#x440;&#x441;&#x438;&#x442;&#x435;&#x442;&#x443;](../../.gitbook/assets/image%20%282%29.png)

{% file src="../../.gitbook/assets/dogovor-14.y26.31.0004.pdf" caption="Договор субсидии 2014 года Сибирскому федеральному университету" %}

## Взаимосвязь

| Сущность | Связь |
| :--- | :--- |
| [Бюджетная роспись](budgetrosp.md) | Субсидия и бюджетная роспись связаны через код бюджетной классификации детально описанный в суммах подлежащих перечислению по кодам КБК в карточке субсидии |
| [Государственные организации](orgsinfo.md) | Субсидия всегда привязана к организации являющейся распределителем и организации являющейся получателем субсидии обе из которых привязаны к сводному реестру участников и неучастников бюджетного процесса |

## Источники данных

<table>
  <thead>
    <tr>
      <th style="text-align:left">&#x418;&#x441;&#x442;&#x43E;&#x447;&#x43D;&#x438;&#x43A;</th>
      <th style="text-align:left">&#x41E;&#x43F;&#x438;&#x441;&#x430;&#x43D;&#x438;&#x435;</th>
      <th style="text-align:left">&#x424;&#x43E;&#x440;&#x43C;&#x430;&#x442;&#x44B;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left"><a href="https://budget.gov.ru/rs">&#x420;&#x435;&#x435;&#x441;&#x442;&#x440; &#x441;&#x43E;&#x433;&#x43B;&#x430;&#x448;&#x435;&#x43D;&#x438;&#x439; &#x43E; &#x43F;&#x440;&#x435;&#x434;&#x43E;&#x441;&#x442;&#x430;&#x432;&#x43B;&#x435;&#x43D;&#x438;&#x438; &#x444;&#x435;&#x434;&#x435;&#x440;&#x430;&#x43B;&#x44C;&#x43D;&#x44B;&#x43C; &#x431;&#x44E;&#x434;&#x436;&#x435;&#x442;&#x43E;&#x43C; &#x441;&#x443;&#x431;&#x441;&#x438;&#x434;&#x438;&#x439;, &#x431;&#x44E;&#x434;&#x436;&#x435;&#x442;&#x43D;&#x44B;&#x445; &#x438;&#x43D;&#x432;&#x435;&#x441;&#x442;&#x438;&#x446;&#x438;&#x439;, &#x43C;&#x435;&#x436;&#x431;&#x44E;&#x434;&#x436;&#x435;&#x442;&#x43D;&#x44B;&#x445; &#x442;&#x440;&#x430;&#x43D;&#x441;&#x444;&#x435;&#x440;&#x442;&#x43E;&#x432;</a>
      </td>
      <td style="text-align:left">&#x420;&#x435;&#x435;&#x441;&#x442;&#x440; &#x43D;&#x430; <a href="../../gis/public/epbs.md">&#x415;&#x434;&#x438;&#x43D;&#x43E;&#x43C; &#x43F;&#x43E;&#x440;&#x442;&#x430;&#x43B;&#x435; &#x431;&#x44E;&#x434;&#x436;&#x435;&#x442;&#x43D;&#x43E;&#x439; &#x441;&#x438;&#x441;&#x442;&#x435;&#x43C;&#x44B;</a> &#x441;&#x43E;&#x434;&#x435;&#x440;&#x436;&#x438;&#x442;
        &#x441;&#x432;&#x435;&#x434;&#x435;&#x43D;&#x438;&#x44F; &#x43E; &#x432;&#x441;&#x435;&#x445;
        &#x441;&#x443;&#x431;&#x441;&#x438;&#x434;&#x438;&#x44F;&#x445; &#x43F;&#x440;&#x435;&#x434;&#x43E;&#x441;&#x442;&#x430;&#x432;&#x43B;&#x44F;&#x435;&#x43C;&#x44B;&#x445;
        &#x438;&#x437; &#x444;&#x435;&#x434;&#x435;&#x440;&#x430;&#x43B;&#x44C;&#x43D;&#x43E;&#x433;&#x43E;
        &#x431;&#x44E;&#x434;&#x436;&#x435;&#x442;&#x430;</td>
      <td style="text-align:left">
        <p>HTML</p>
        <p>JSON</p>
      </td>
    </tr>
  </tbody>
</table>## Ссылки

1. [Сведения о соглашений о предоставлении федеральным бюджетом субсидий, бюджетных инвестиций, межбюджетных трансфертов](http://budget.gov.ru/epbs/faces/p/%D0%91%D1%8E%D0%B4%D0%B6%D0%B5%D1%82/%D0%A0%D0%B0%D1%81%D1%85%D0%BE%D0%B4%D1%8B/%D0%A0%D0%B5%D0%B5%D1%81%D1%82%D1%80%20%D1%81%D0%BE%D0%B3%D0%BB%D0%B0%D1%88%D0%B5%D0%BD%D0%B8%D0%B9?_adf.ctrl-state=mgfi7r3xo_4&regionId=45)
2. [Реестр соглашений о предоставлении федеральным бюджетом субсидий, бюджетных инвестиций, межбюджетных трансфертов](http://budget.gov.ru/rs)



