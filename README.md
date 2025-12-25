# Отчет по лабраторной работе на тему "Основы Ansible в DevOps"
***

## Введение

Цель данной лабораторной работы — освоить практические навыки работы с Ansible, инструментом для автоматизации конфигурации и управления инфраструктурой. В рамках работы предстояло настроить управляющую машину с Ansible, развернуть управляемый хост в Docker-контейнере, настроить SSH-подключение без пароля, создать инвентарный файл и выполнить 

***
## Ход работы
### Задание № 1
Установили python и ansible
<img width="643" height="193" alt="image" src="https://github.com/user-attachments/assets/26cfb14e-75ae-4e73-b2dd-89632965512d" />

Сгенерировали SSH ключевой пары на управляющей машине
<img width="617" height="55" alt="image" src="https://github.com/user-attachments/assets/85b503cf-28fb-474f-a0a5-ca3ee181811b" />

Созданили Dockerfile для управляемого хоста, docker-compose.yml и собрали и запустили контейнер
<img width="985" height="520" alt="image" src="https://github.com/user-attachments/assets/c644f7a0-d389-4adc-83c1-44f1d4f29982" />
<img width="981" height="87" alt="image" src="https://github.com/user-attachments/assets/34c45877-b5ad-428a-9398-ef33a1de2643" />

Проверили SSH подключение к контейнеру
<img width="873" height="297" alt="image" src="https://github.com/user-attachments/assets/2e5360a9-f893-4abb-b38d-c3e6fcb281df" />

Создали и проверили инвентарный файл Ansible (inventory)
<img width="812" height="426" alt="image" src="https://github.com/user-attachments/assets/817789e4-5f02-47a3-99c5-22467c1bc580" />

Проверили подключение Ansible к управляемому хосту
<img width="857" height="681" alt="image" src="https://github.com/user-attachments/assets/fd5920f7-7cbb-4770-900c-829802c003d7" />
<img width="1110" height="76" alt="image" src="https://github.com/user-attachments/assets/5263365a-8311-47d8-8385-a61bce3235e2" />

***
### Задание №2

Получили информацию о ядрах CPU управляемого хоста, список всех пользователей и проверили свободное место на диске:
<img width="947" height="153" alt="image" src="https://github.com/user-attachments/assets/068f2487-e879-48fa-8461-ba4eeb1e3520" />
<img width="908" height="162" alt="image" src="https://github.com/user-attachments/assets/33e4e9cd-0bc6-4cb6-b468-6ee643dc4e25" />
<img width="909" height="452" alt="image" src="https://github.com/user-attachments/assets/65361b2c-a9ca-4e0d-a2e3-7e3266f80b2c" />

***
### Задание №3

Создайли новый playbook `task3_files.yml`:

<img width="744" height="691" alt="image" src="https://github.com/user-attachments/assets/9ce49b3d-e4a5-4047-9953-6668462391d8" />

и запустили его:
<img width="935" height="712" alt="image" src="https://github.com/user-attachments/assets/63d1df0f-c518-41ba-94a9-f3704fc207bf" />

