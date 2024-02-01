# Обновление CentOS

CentOS для обновления использует пакетный менеджер Yum (Yellowdog Updater, Modified). Для обновления CentOS необходимо:

  1. Удалить все пакеты и метаданные:
```bash
yum clean all
```
  2. Получить список обновлений:
```bash
yum list updates
```
  3. Обновить CentOS:
```bash
yum update
```
  4. Перезагрузить CentOS:
```bash
reboot
```