Research on data about Russian film distribution.
Description of the project
The Ministry of Culture of the Russian Federation is the client for this research. We need to study the Russian film distribution market and identify current trends. We will focus on films that have received government support. We will try to answer the question of how interesting such films are to the viewer. Our task is to preprocess the data and study it in order to find interesting characteristics and dependencies that exist in the Russian film distribution market. We will work with data published on the portal of open data of the Ministry of Culture of the Russian Federation. The data set contains information on film distribution licenses, collections and government support for films, as well as information from the Kinopoisk website.

Описание данных:
The mkrf_movies table contains information from the state licensing registry. One film can have several distribution licenses. The budget column already includes the full amount of government support. The data in this column is only for those films that received government support.

title — movie title;
puNumber — license number;
show_start_date - movie premiere date;
type — movie type;
film_studio - production studio;
production_country - country of origin;
director — director;
producer — producer;
age_restriction - age category;
refundable_support — amount of state support repayable funds;
nonrefundable_support - the amount of non-refundable state support funds;
financing_source - source of government funding;
budget - the total budget of the movie;
ratings — movie rating on KinoPoisk;
genres — movie genre;
box_office — revenue in rubles.
The mkrf_shows table contains information about movie screenings in Russian cinemas.

puNumber — license number;
box_office — revenue in rubles.

--------------------------------------------

Исследование данных о российском кинопрокате
Описание проекта
Заказчик исследования — Министерство культуры Российской Федерации. Нам нужно изучить рынок российского кинопроката и выявить текущие тренды. Уделим внимание фильмам, которые получили государственную поддержку. Попробуем ответить на вопрос, насколько такие фильмы интересны зрителю. Наша задача — выполнить предобработку данных и изучить их, чтобы найти интересные особенности и зависимости, которые существуют на рынке российского кинопроката. Мы будем работать с данными, опубликованными на портале открытых данных Министерства культуры РФ. Набор данных содержит информацию о прокатных удостоверениях, сборах и государственной поддержке фильмов, а также информацию с сайта КиноПоиск.

Описание данных:
Таблица mkrf_movies содержит информацию из реестра прокатных удостоверений. У одного фильма может быть несколько прокатных удостоверений. Cтолбец budget уже включает в себя полный объём государственной поддержки. Данные в этом столбце указаны только для тех фильмов, которые получили государственную поддержку.

title — название фильма;
puNumber — номер прокатного удостоверения;
show_start_date — дата премьеры фильма;
type — тип фильма;
film_studio — студия-производитель;
production_country — страна-производитель;
director — режиссёр;
producer — продюсер;
age_restriction — возрастная категория;
refundable_support — объём возвратных средств государственной поддержки;
nonrefundable_support — объём невозвратных средств государственной поддержки;
financing_source — источник государственного финансирования;
budget — общий бюджет фильма;
ratings — рейтинг фильма на КиноПоиске;
genres — жанр фильма;
box_office — сборы в рублях.
Таблица mkrf_shows содержит сведения о показах фильмов в российских кинотеатрах.

puNumber — номер прокатного удостоверения;
box_office — сборы в рублях.
