# Домашнее задание к занятию 14 «Средство визуализации Grafana» - Скрыпников Илья
Задание 1
![image](https://github.com/user-attachments/assets/0a024796-6317-441b-88f7-d365778b542d)

#
Задание 2
![image](https://github.com/user-attachments/assets/b348d10a-fe68-43c4-bb35-168a37db507e)
,,,
100 - avg(rate(node_cpu_seconds_total{mode="idle"}[5m])) * 100
rate(node_cpu_seconds_total{mode="system",cpu="cpu1"}[5m]) * 100
rate(node_cpu_seconds_total{mode="system",cpu="cpu5"}[5m]) * 100
rate(node_cpu_seconds_total{mode="system",cpu="cpu15"}[5m]) * 100
node_memory_MemAvailable_bytes
node_filesystem_free_bytes{fstype!="tmpfs"}

,,,
#

![image](https://github.com/user-attachments/assets/e304f8db-2159-4142-9f61-560468bf8aad)

#
