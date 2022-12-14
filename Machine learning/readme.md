# Стратегия взаимодействия с клиентами фитнесс - центров "Культурист - Датасаентист"

## Описание проекта

Сеть фитнес-центров «Культурист-датасаентист» разрабатывает стратегию взаимодействия с клиентами на основе аналитических данных.
Распространённая проблема фитнес-клубов и других сервисов — отток клиентов.
Чтобы бороться с оттоком, отдел по работе с клиентами «Культуриста-датасаентиста» перевёл в электронный вид множество клиентских анкет. Наша задача — провести анализ и подготовить план действий по удержанию клиентов.

А именно:
* научиться прогнозировать вероятность оттока (на уровне следующего месяца) для каждого клиента;
* сформировать типичные портреты клиентов: выделить несколько наиболее ярких групп и охарактеризовать их основные свойства;
* проанализировать основные признаки, наиболее сильно влияющие на отток;
* сформулировать основные выводы и разработать рекомендации по повышению качества работы с клиентами:

        1) выделить целевые группы клиентов;
        
        2) предложить меры по снижению оттока;
        
        3) определить другие особенности взаимодействия с клиентами.
        

## Схема анализа


<div class="toc"><ul class="toc-item"><li><span><a href="#Шаг.-Загрузка-и-описание-данных." data-toc-modified-id="Шаг.-Загрузка-и-описание-данных.-1"><span class="toc-item-num">1&nbsp;&nbsp;</span>Шаг. Загрузка и описание данных.</a></span></li><li><span><a href="#Шаг.-Исследовательский-анализ-данных-(EDA)" data-toc-modified-id="Шаг.-Исследовательский-анализ-данных-(EDA)-2"><span class="toc-item-num">2&nbsp;&nbsp;</span>Шаг. Исследовательский анализ данных (EDA)</a></span></li><li><span><a href="#Шаг.-Построение-модели-прогнозирования-оттока-пользователей" data-toc-modified-id="Шаг.-Построение-модели-прогнозирования-оттока-пользователей-3"><span class="toc-item-num">3&nbsp;&nbsp;</span>Шаг. Построение модели прогнозирования оттока пользователей</a></span></li><li><span><a href="#Шаг.-Кластеризация-клиентов." data-toc-modified-id="Шаг.-Кластеризация-клиентов.-4"><span class="toc-item-num">4&nbsp;&nbsp;</span>Шаг. Кластеризация клиентов.</a></span><ul class="toc-item"><li><span><a href="#Распределение-признаков-по-кластерам" data-toc-modified-id="Распределение-признаков-по-кластерам-4.1"><span class="toc-item-num">4.1&nbsp;&nbsp;</span>Распределение признаков по кластерам</a></span></li><li><span><a href="#Доли-оттока-по-кластерам" data-toc-modified-id="Доли-оттока-по-кластерам-4.2"><span class="toc-item-num">4.2&nbsp;&nbsp;</span>Доли оттока по кластерам</a></span></li></ul></li><li><span><a href="#Общий-вывод" data-toc-modified-id="Общий-вывод-5"><span class="toc-item-num">5&nbsp;&nbsp;</span>Общий вывод</a></span></li></ul></div>

