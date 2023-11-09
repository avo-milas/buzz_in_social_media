# Buzz in social media

Датасет содержит примеры buzz events ("шумных событий") из социальной сети - Twitter

Данные могут быть получены по [ссылке](https://archive.ics.uci.edu/static/public/248/buzz+in+social+media.zip)





Датасет представляет из себя $77$ колонок, по $7$ измерений во времени на показатель

Сами показатели:

### NCD 

This feature measures the number of discussions created at time step t and involving the instance's topic.

Количество тредов, созданных за определенный период

### AI

This feature measures the number of new authors interacting on the instance's topic at time t (i.e. its popularity)

Количество новых для темы авторов, взаимодуйствующих с постами

### AS(NA)

This feature is a measure of the attention payed to a the instance's topic on a social media.

Нормированный показатель, измеряющий внимание к теме через количество людей


### BL

The burstiness level for a topic z at a time t is defined as the ratio of ncd and nad

Отношение количества новых тредов ко всем тредам, с которыми взаимодействуют за данный период (новизна темы)

### NAC

This feature measures the total number of atomic containers generated through the whole social media on the instance's topic until time t.



### AS(NAC)

This feature is a measure of the attention payed to a the instance's topic on a social media.

Нормированный показатель, измеряющий внимание к теме через количество взимодействий

### CS

This feature is a measure of spreading of contributions over discussion for the instance's topic at time t.

"Расползание" взаимодействий - очень скореллировано с BL

### AT

This feature measures the average number of authors interacting on the instance's topic within a discussion.

Среднее количество авторов, взаимодействующих с постами по теме

#### NA

This feature measures the number of authors interacting on the instance's topic at time t.

Общее количество авторов, взаимодействующих с постами по теме

### ADL

This feature directly measures the average length of a discussion belonging to the instance's topic.

Средняя длина дискуссии
          

### NAD

This features measures the number of discussions involving the instance's topic until time t.

Количество дискуссий по теме
