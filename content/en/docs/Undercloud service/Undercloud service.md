+++
Undercloud_service = "Undercloud service"
date = ""
description = ""
draft = true
linkTitle = "Undercloud service"

+++
Создание инфраструктуры для разработки  
<br></br>

# **Строим и поддерживаем**

платформы и сервисы
<br></br>
<br></br>
### <center>**Основа вашей инфраструктуры для разработки и прода**</center>
#### **Платформа виртуализации**
* Подбираем платформу на базе технологии kvm (OpenStack, oVirt, Opennebula и т.д.) 
* Ускоряем предоставление выч. ресурсов, используя API платформы. 
* Внедряем системы логирования и мониторинга с различными способами оповещения.
* Сокращаем сроки внедрения, применяя типовые решений.

#### **Managed Kubernetes**
* Внедряем платформу Kubernetes для управления вашими приложениями.  
* Повышаем стабильность платформы. 
* Поддерживаем регулярные обновления. 
* Предоставляем встроенный мониторинг компонентов k8s и приложений

#### **Высокодоступное хранилище данных**
* Внедряем SDS на базе ceph или linstor. (Дима думает) 
* Проектируем с нуля или на внедряем на уже существующее железо

#### **Дополнительные возможности внедряемых систем**
* Быстрое масштабирование компонентов внедряемых платформ. (думает Дима)
* Использование оборудования любого производителя
* Простой переход к гибридному сценарию работы платформы. 


### <center>**Стабильные сервисы для работы ваших приложений**</center>

#### **Снижение времени восстановления после аварий**

* Создаем DR план для ваших инфраструктурных сервисов
* Создаем план восстановления после аварии для ваших инфраструктурных сервисов
* Настраиваем системы процесс бэкапирования БД с проверкой на целостность

#### **Работа приложений без простоев**

* Внедряем архитектуру высокой доступности для инфраструктурных сервисов
* Proxysql - создаем роутинг данных любой сложности

#### **Масштабирование с ростом нагрузки. Понятный рост инфраструктуры**

* Проводим нагрузочные тестирования для определения ограничений сервиса и возможностей горизонтального масштабирования (мы попытались разделить на две части этот перегруженный пункт)
* Определяем ограничения сервиса с помощью нагрузочных тестов
* Решаем проблемы горизонтального масштабирования
* Повышаем производительность инфраструктурных сервисов на бою и в деве

### <center>**Поддержка внедренных решений и инфраструктуры**</center>
#### **Берем работу с непрофильными задачами на себя**
* Обслуживаем внедренные решения и инфраструктуру
* Предотвращаем инциденты в работе инфраструктуры
* Обеспечиваем рост инфраструктуры соответственно росту нагрузки
