# Оценка качества нового алгоритма дейтинг приложения 💗
## ⚙️ Инструменты и библиотеки:
тест Шапиро-Уилка | T-тест 

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original-wordmark.svg" title="Jupyter" alt="Jupyter" width="40" height="40"/>&nbsp;
  <img src="https://pandas.pydata.org/static/img/pandas_white.svg" title="Pandas" alt="Pandas" height="40"/>&nbsp;
  <img src="https://camo.githubusercontent.com/6631ab3e404c95feff2366126736bf6b3759e4be11357ea07405a3527b9a3138/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6e756d70792d2532333031333234332e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6e756d7079266c6f676f436f6c6f723d7768697465" title="Numpy" alt="Numpy" height="30"/>&nbsp;
  <img src="https://pingouin-stats.org/build/html/_images/logo_pingouin.png" title="Pingouin" alt="Pingouin" height="30"/>&nbsp;
  <img src="https://avatars.mds.yandex.net/i?id=ed4bb20472a95e34f0ee6dc8de3069ccf373f67d-8497452-images-thumbs&n=13" title="Statsmodels" alt="Statsmodels" height="30"/>&nbsp;
  <img src="https://camo.githubusercontent.com/9e175adcb5e76a230ffd53ed1e78034277d31171b77358865b2be148d0b523d3/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d6174706c6f746c69622d2532336666666666662e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d4d6174706c6f746c6962266c6f676f436f6c6f723d626c61636b" title="Mathplotlib" alt="Mathplotlib" height="30"/>&nbsp;
  <img src="https://avatars.mds.yandex.net/i?id=3b1d13a52ed933827565a138d9a0f7b8cc7df932-12490006-images-thumbs&n=13" title="Seaborn" alt="Seaborn" height="30"/>&nbsp;
</div>

## 👩🏻‍💻 Задачи:
- Провести предобработку данных;
- Выбрать метрики для оценки качества работы алгоритма дейтинг приложения;
- Расчитать метрики;
- Провести тест Шапиро-Уилка;
- Оценить, правда ли, что новый алгоритм улучшил качество сервиса;

## 🔎 Выводы:
- Метрики, которые были использованы в ходе проведения теста: CTR, соотношение метчей и не-метчей, количество свайпов вправо;
- Тест тест Шапиро-Уилка показал, что распределение CTR является нормальным;
- Пользователи, которые используют новый алгоритм для поиска подходящих анкет имеют больший CTR, чем контрольная группа пользователей;
- Соотношение статистически значимо отличается в контрольной и экспериментальной группе (в эксперментальной группе соотношение метчей к не-метчей выше)
- Средние значения количества метчей в экспериментальной и контрольной выборках статистически значимо различаются (в эксперментальной группе количество метчей выше)
- Проведенный эксперимент показал, что с высокой долей вероятности новый алгоритм оказал положительное влияние на поиск наиболее подходящих анкет. Раскатываем алгоритм на всех пользователей.
