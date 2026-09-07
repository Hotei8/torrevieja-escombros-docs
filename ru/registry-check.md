---
title: "Проверка реестра gestores de residuos — Торревьеха"
lang: ru
translations:
  es: /registro-gestores.html
  en: /en/registry-check.html
  ru: /ru/registry-check.html
---

**Дата проверки:** 2026-09-04 (первичная 2026-09-01 — см. «Исправление» ниже)
**Источник:** публичный реестр Generalitat Valenciana — https://residuos.gva.es/res_buscaweb/
**Метод:** поиск по Provincia = Alicante, Municipio = Torrevieja; отдельно по категориям «Residuos NO peligrosos (RNP)» и «Residuos peligrosos (RP)», по каждому типу операции (almacenamiento / tratamiento / eliminación). Скриншоты — в папке `evidence/`.

## Ключевой вывод

Авторизация gestor привязана к **конкретной установке и адресу**, а не к человеку — поэтому для проверки не нужно знать имя владельца участка. Все авторизованные установки Торревьехи находятся по конкретным адресам (промзона Casa Grande, Camino del Cementerio, Partida La Marquesa и др.). **Полосы земли у урбанизаций среди них нет.**

⚠️ Пределы проверки: это просмотр публичного веб-реестра по одному муниципалитету; он не исключает уведомительных режимов, мобильных операций или записей по соседним муниципалитетам. Корректная формулировка: «в просмотренной части публичного реестра авторизованной установки по данному адресу не найдено». Перед официальной подачей — повторить со свежей датой.

## Результаты (Торревьеха)

| Категория | Тип операции | Результат |
|---|---|---|
| RNP (неопасные) | Gestores de almacenamiento | 4 установки (Casa Grande ×3 адреса, Acacio Rebagliato 5) |
| RNP | Gestores de tratamiento | 8 установок (список ниже) |
| RNP | Gestores de eliminación (полигон) | **No se encontraron registros** — ноль |
| RP (опасные) | Gestores de almacenamiento | 3 установки (Reciclajes Casa Grande, Reciclajes Vegabaja, Mostafa Salhi) |
| RP | Gestores de tratamiento y de eliminación | 3 установки (Reciclajes Vegabaja, Recuperaciones y Reutilizaciones Torrevieja, Mostafa Salhi) |

## Все авторизованные gestores de tratamiento (RNP) в Торревьехе

| Центр | NIMA | Адрес |
|---|---|---|
| EXPLANACIONES DEL MEDITERRANEO, S.L. | 0300006297 | San Policarpo, 33 |
| AYUNTAMIENTO DE TORREVIEJA | 0300006890 | Camino del Cementerio, s/n |
| RECICLAJES CASA GRANDE, S.L. | 0300008039 | Pol. Ind. Casa Grande, C/ Antonio Ruiz Coves, 4 |
| RECICLAJES VEGABAJA, S.L. | 0300008534 | C/ Acacio Rebagliato Pamies 5 |
| RECUPERACIONES Y REUTILIZACIONES TORREVIEJA, S.L. | 0300015602 | Pol. Ind. Casagrande, C/ María Humildad Jiménez 72 |
| RECICLAJES NICOLAS Y TAIFI, S.C. | 0300007926 | C/ Bella Antonia 25 |
| PASTOR MEDINA, S.A. | 0300008257 | Partida La Marquesa, Polígono 2, Parcela 264 |
| MOSTAFA SALHI | 0300011742 | Pol. Ind. Casagrandes, C/ Acacio Rebagliato esq. C/ Bautista Bertomeu Sober |

## Исправление к проверке 2026-09-01

Первый прогон 01.09 показал «Gestores de almacenamiento (RNP) — ноль записей». Повторные прогоны 04.09 (дважды) стабильно показывают **4 установки**. Причина — ошибка при первой проверке (форма отправилась до того, как подгрузился список типов операций). Вывод «ноль хранения» был **ошибочным** и удалён; на общий вывод (у полос нет авторизации) это не влияет — все 4 установки находятся в промзоне.

## Формулировка для жалобы (вставлять как есть)

> Consultado el registro público de productores y gestores de residuos de la Generalitat Valenciana (https://residuos.gva.es/res_buscaweb/) con fecha [ФАКТИЧЕСКАЯ ДАТА], en el término municipal de Torrevieja únicamente constan instalaciones autorizadas de gestión de residuos en domicilios distintos (polígono industrial Casa Grande y otros); **no consta ninguna instalación autorizada en la parcela con referencia catastral [REFERENCIA]**.

## Как повторить проверку вручную (2 минуты)

1. Открыть https://residuos.gva.es/res_buscaweb/
2. Categoría → «Residuos NO peligrosos (RNP)» (после этого появится список «Tipo de operación»)
3. Tipo de operación → «Gestores de almacenamiento» (потом повторить с tratamiento и eliminación; затем то же для категории «Residuos peligrosos (RP)»)
4. Provincia → Alicante, Municipio → Torrevieja
5. Нажать «Buscar» → сравнить адреса из списка с адресом полосы, снять скриншот с датой.

---

# Сверка ордонанса по официальному тексту

**Файл:** `ordenanza-aseo-urbano-torrevieja-BOP-40-2026-02-27.pdf` (скачан с torrevieja.es 04.09.2026, 45 страниц). Вступление в силу: «Esta Ordenanza entrará en vigor tras su publicación en el Boletín Oficial de la Provincia» (Disposición final) — публикация BOP nº 40 от 27.02.2026.

Проверено дословно по тексту PDF:

| Статья | Текст (проверен) |
|---|---|
| Art. 6.h) | «Arrojar poda, escombro, aceite o cualquier otro residuo peligroso en vía pública o en solares, públicos o privados» — совпадает |
| Art. 21.3 | «Se prohíbe expresamente el vertido de residuos, y en particular los de construcción y demolición, en la vía pública o en solares y parcelas, públicas o privadas» — совпадает |
| Art. 42.1 | «Está prohibido arrojar a la vía pública, parcelas particulares o públicas y solares, cualquier tipo de residuo: basuras, escombros, podas, enseres…» — совпадает |
| Art. 50.m) | «La falta de limpieza, desinfección o desratización de las parcelas…» — leve, совпадает |
| Art. 51.a) | «El abandono, vertido o eliminación incontrolado de cualquier tipo de residuos municipales sin que se haya puesto peligro grave para la salud…» — grave, совпадает |
| Art. 52.a) | «El abandono o vertido incontrolado de cualquier tipo de residuos… abandono o vertido incontrolado de residuos peligrosos» — muy grave, совпадает |
| Шкала | «Muy graves: Multas desde 600.001 hasta 3.500.000 €»; за art. 42.1 в таблице санкций — 10.000 € / 5.000 € (досрочная оплата) — совпадает |
