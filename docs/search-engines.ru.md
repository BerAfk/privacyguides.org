---
title: Поисковые системы
icon: material/search-web
---

Используйте поисковую систему, которая не строит рекламный профиль на основе ваших запросов.

Приведенные здесь рекомендации основаны на политиках конфиденциальности этих сервисов. Не существует **никакой гарантии** того, что эти политики конфиденциальности будут соблюдены.

Советуем использовать [VPN](/vpn) или [Tor](https://www.torproject.org/), если ваша модель угроз требует скрытия вашего IP-адреса от поискового провайдера.

### DuckDuckGo

!!! recommendation

    ![Логотип DuckDuckGo](/assets/img/search-engines/duckduckgo.svg){ align=right }
    
    **DuckDuckGo** - популярная поисковая система, которая также используется по умолчанию в браузере Tor.
    
    DuckDuckGo использует коммерческий API Bing и [другие источники](https://help.duckduckgo.com/results/sources) для предоставления своих поисковых данных.
    
    [Посетить duckduckgo.com](https://duckduckgo.com){ .md-button .md-button--primary } [:pg-tor:](https://duckduckgogg42xjoc72x3sjasowoarfbgcmvfimaftt6twagswzczad.onion){ .md-button } [Политика конфиденциальности](https://duckduckgo.com/privacy){ .md-button }

!!! note

    DuckDuckGo базируется в 🇺🇸 США. В их [Политике конфиденциальности](https://duckduckgo.com/privacy) говорится, что они регистрируют ваш поисковый запрос, но не ваш IP или любую другую идентифицирующую информацию.

В DuckDuckGo есть [лёгкая](https://duckduckgo.com/lite) и [html-only](https://duckduckgo.com/html) версия, обе из которых [не требуют JavaScript](https://help.duckduckgo.com/features/non-javascript) и могут быть использованы с [onion адресом DuckDuckGo](https://duckduckgogg42xjoc72x3sjasowoarfbgcmvfimaftt6twagswzczad.onion) (добавьте [/lite](https://duckduckgogg42xjoc72x3sjasowoarfbgcmvfimaftt6twagswzczad.onion/lite) или [/html](https://duckduckgogg42xjoc72x3sjasowoarfbgcmvfimaftt6twagswzczad.onion/html) для соответствующей версии).

### Startpage

!!! recommendation

    ![Логотип Startpage](/assets/img/search-engines/startpage.svg){ align=right }
    
    **Startpage** - это поисковая система, которая предоставляет результаты поиска из Google. Это очень удобный способ получить поисковые результаты Google, не сталкиваясь с такими темными паттернами, как сложные капчи или отказ в доступе из-за того, что вы используете [VPN](/vpn) или [Tor](https://www.torproject.org/download/).
    
    [Посетить startpage.com](https://www.startpage.com){ .md-button .md-button--primary } [Политика конфиденциальности](https://www.startpage.com/en/privacy-policy){ .md-button }

!!! note

    Startpage базируется в 🇳🇱 Нидерландах. Согласно их [Политике конфиденциальности](https://www.startpage.com/en/privacy-policy/), они хранят только такие данные, как: операционная система, тип браузера и язык. Они не регистрируют ваш IP-адрес, поисковые запросы или другую идентифицирующую информацию. Startpage проксирует Google Search, поэтому Google имеет доступ к вашим поисковым запросам.

Основным акционером Startpage является компания System1, занимающаяся рекламными технологиями. Мы не думаем, что это проблема, поскольку у них есть своя политика конфиденциальности. Команда Руководства По Приватности обратилась в Startpage [еще в 2020 году](https://web.archive.org/web/20210118031008/https://blog.privacytools.io/relisting-startpage/) за разъяснениями и была удовлетворена полученными ответами.

### Mojeek

!!! recommendation

    ![Логотип Mojeek](/assets/img/search-engines/mojeek.svg){ align=right }
    
    **Mojeek** - еще одна поисковая система, сохраняющая вашу конфиденциальность. Они используют свой собственный поисковый робот для предоставления поисковых данных.
    
    [Посетить mojeek.com](https://www.mojeek.com){ .md-button .md-button--primary } [Политика конфиденциальности](https://www.mojeek.com/about/privacy){ .md-button }

!!! note

    Компания расположена в 🇬🇧 Великобритании. Согласно их [Политике конфиденциальности](https://www.mojeek.com/about/privacy/), они регистрируют страну, время, запрашиваемую страницу и данные о реферере каждого запроса. IP-адреса не логируются.

### Searx

!!! recommendation

    ![Логотип Searx](/assets/img/search-engines/searx.svg){ align=right }
    
    **Searx** - это метапоисковая система [с открытым кодом](https://github.com/asciimoo/searx), которую можно развернуть на своем сервере, агрегирующая результаты других поисковых систем и не хранящая информацию о своих пользователях. Существует [список публичных экземпляров](https://searx.space/) Searx.
    
    [Посетить searx.me](https://searx.me){ .md-button .md-button--primary } [:pg-tor:](http://searxspbitokayvkhzhsnljde7rqmn7rvoga6e4waeub3h7ug3nghoad.onion){ .md-button }

Searx - это посредник между пользователем и поисковыми системами, данные которых он собирает. Ваши поисковые запросы все равно будут отправляться в поисковые системы, из которых Searx получает результаты.

При самостоятельном хостинге важно, чтобы вашим экземпляром пользовались и другие люди, иначе вы будете выделяться и вас смогут отследить. Вы должны быть осторожны с тем, где и как вы размещаете Searx, поскольку другие люди, ищущие незаконный контент на вашем экземпляре, могут привлечь нежелательное внимание властей.

Если вы используете чужой экземпляр Searx, обязательно ознакомьтесь с политикой конфиденциальности этого конкретного экземпляра. Экземпляры Searx могут быть изменены их владельцами и поэтому могут иметь политику конфиденциальности, отличную от оригинальной. Некоторые экземпляры имеют Tor адреса .onion, которые могут обеспечить некоторую конфиденциальность, если ваши поисковые запросы не содержат ПИИ (персонально идентифицируемой информации).
