### Monitoring Engineer / NOC Engineer

Инженер мониторинга и автоматизации ИТ-инфраструктуры. Отвечаю за мониторинг
парка серверов и рабочих станций, разбираюсь в первопричинах инцидентов, а не
только в симптомах, и пишу инструменты, которые убирают ручную рутину из
поддержки и эксплуатации.

**Чем занимаюсь**

- Мониторинг инфраструктуры: сбор метрик, алертинг (Zabbix, Prometheus/Alertmanager),
  разбор инцидентов.
- Детекция событий безопасности Active Directory по логам Windows Security
  (Graylog, Winlogbeat) — неудачные входы, блокировки, просроченные пароли.
- Автоматизация администрирования Windows/AD на PowerShell.
- Инструменты для 1-й и 2-й линии поддержки.

**Стек**

* Мониторинг: Zabbix, Graylog, Winlogbeat, SNMP
* Автоматизация: PowerShell, Windows Server, Active Directory, Bash
* Инфраструктура и безопасность: Microsoft Exchange, FreePBX/Asterisk, Nginx, Kaspersky Security Center, SSL/TLS
* Изучаю / внедряю: Prometheus-стек (Grafana, Alertmanager), Docker, Linux

**Проекты**

- [zabbix-telegram-router](https://github.com/mrklv01/zabbix-telegram-router) —
  маршрутизация алертов Zabbix в Telegram-топики на основе тегов, с резервным
  разделом по умолчанию.
- [monitoring-stand](https://github.com/mrklv01/monitoring-stand) — стенд
  мониторинга Prometheus + Grafana + Alertmanager в Docker, в двух вариантах
  (Windows + Linux VPS): конфигурация как код (provisioning), алерты в Telegram
  с HTML-шаблонами, служебные порты закрыты от интернета (SSH-туннели).
- [graylog-windows-security-detections](https://github.com/mrklv01/graylog-windows-security-detections) —
  каталог детектов Windows Security в Graylog: неудачные входы, блокировки
  учётных записей, просроченные пароли (Event ID 4625/4740), с оповещением
  в Telegram.
- [support-toolkit](https://github.com/mrklv01/support-toolkit) — GUI-оснастка
  на PowerShell/WinForms: 12 операций удалённого администрирования рабочих
  станций в одном окне (WinRM), единая авторизация и аудит-лог.
- [master-hr-predictive-analytics](https://github.com/mrklv01/master-hr-predictive-analytics) —
  HR-Agent: инструмент предиктивного анализа рисков выгорания персонала по
  данным ITSM (Next.js + TypeScript, LLM-анализ, PDF-отчёты). Магистерская работа.

**Связь**

- Telegram: [@mrklv_vn](https://t.me/mrklv_vn)
