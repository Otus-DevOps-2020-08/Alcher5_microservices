# Alcher5_microservices
Alcher5 microservices repository
## Домашнее задание к лекции №16
### Выполненные действия

- Создана и настроена новая ветка `microservices` .

- Установлен **Docker** и **docker-machine**.

- Запущены и просмотрены готовые тестовые образы,  изучены команды по управлению.

- Задание со **`*`**: Вывод команды  `docker inspect` записан в файл и описана разница образа и контейнера.

- Настроен **YC** и создан новый инстанс с помощью **docker-machine**.

- Собран собственный образ с приложением на основе файла `Dockerfile`.

- Собственный образ выгружен в **Docker hub** .

- Сделаны проверки комманд в выполняемом контейнере.

- Создана инфраструктура под **Docker**.

- Добавлено создание образа с помощью **packer** (из `docker-monolith/infra`):
`packer build -var-file=packer/variables.json packer/docker.json`

- Добавлен **Vagrantfile** с помощью которого можно проверить **Ansible playbook** из директории `docker-monolith/infra/ansible` командой: `vagrant up` 

- Добавлена возможность поднятия инстансов в **YC** через **Terraform** из директории    `docker-monolith/infra/terraform` командой: `terraform apply -auto-approve`


