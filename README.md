# Whois

Первое, собственное приложение реализованное в процессе реализации итогового задания на курсе "Мобильная разработка" от компании от ООО "Инвольта Образование".

Требования к приложению:
Создать мобильное приложение «Whois», используя открытое Web API (https://whois.whoisxmlapi.com) 
- Приложение должно показывать пользователю информацию об интересующем его домене;
- Пользователь должен иметь возможность просматривать всю существующую информацию о доменном имени;
- Приложение должно хранить историю проверок, а также кэшировать информацию по каждому проверенному сайту для доступа к ним без подключения к сети интернет;
- Если пользователь кликает по URL в стороннем приложении, то ему должно быть предложено открыть URL в вашем приложении для его проверки.

Проект реализован с использованием:
- ViewBinding
- С запросом  на APi используя Retrofit2
- Парсинг Json Object
- Сохранение во внутренее хранилище информации с помощью записи методом openFileInput
- Получение из внутреннего хранилища информации  с помощью записи методом openFileOutput
- Вывод первичной информации с помощию RecyclerView
- Вывод подробной информации с использованием ScrollView
- В проекте использовались - coroutines и livedata
