# Testk8s
Test task for MindBox<br>
Для начала хочу попросить указать на возможные ошибки и объяснить их, т.к. самому интересно, как это нужно и лучше всего реализовать.
# Вопросы и решения
1. **Как равномерно распределять поды по зонам или узлам**
 - Реализация topologySpreadConstraints
3. **Как проверить запустилось ли приложение внутри пода?**
 - Реализация readinessProbe
3. **Как узнать, запустился ли под?**
 - Реализация startupProbe
4. **Что делать, если под завис?**
 - Реализация livenessProbe
5. **Как оптимизировать нагрузку на поды?**
 - Реализация HorizontalPodAutoscaler, беря в основу нагрузку на CPU
