# Ansible Role: vector
[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)  

## Description

Роль для разворачивания Vector


## Requirements

- Ansible >= 2.7
- CentOS 7

## Role Variables

Все параметры расположены в  [defaults/main.yml](defaults/main.yml) и могут быть переопределены.

| Имя           | Исходное значение | Описание                        |
| -------------- | ------------- | -----------------------------------|
| `vector_arch` | x86_64 | Архетектура устанавливаемого пакета  |
| `vector_version` | 0.31.0 | Версия устанавливаемого пакета  |
| `vector_config_folder` | /etc/vector | Папка для конфигруционного файла  |
Доп параметры расположены в [vars/main.yml](vars/main.yml)

| Имя           | Исходное значение | Описание                        |
| -------------- | ------------- | -----------------------------------|
| `vector_config` | - | Настройки для сорс и таргет вектора  |
