<p align="center">
  <img height="100" height="auto" src="https://github.com/user-attachments/assets/2d1f1a0e-f8d9-4b24-9c71-c6e3a46d7afc">
</p>

# Dill Testnet

Official documentation:
>- [Validator setup instructions](https://dill.xyz/docs/RunANode/Alps)

Explorer:
>- [Explorer](https://alps.dill.xyz)

### Minimum Hardware Requirements
 - 2x CPUs; the faster clock speed the better
 - 2GB RAM
 - 20GB of storage (SSD or NVME)

### Recommended Hardware Requirements 
 - 4x CPUs; the faster clock speed the better
 - 8GB RAM
 - 256GB of storage (SSD or NVME)

 - Ubuntu 22.04

Устанавливаем ноду:

``sudo apt update & sudo apt upgrade -y``

``sudo apt install ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev curl git wget make jq -y``

``curl -sO https://raw.githubusercontent.com/DillLabs/launch-dill-node/main/dill.sh  && chmod +x dill.sh && ./dill.sh``

**Нажимаем любую клавишу**

![Termius_dqv6KTG8oI](https://github.com/user-attachments/assets/ea9dec0f-94bc-4660-9cf4-f8e2b8795c04)

**Вписываем 1 и нажимаем Enter, после этого появится фраза, которую нужно сохранить. После нажимаем любую клавишу, ждем сохранения файла и еще раз нажимаем любую клавишу**

![Termius_6zJhowHpml](https://github.com/user-attachments/assets/d7683f92-f300-4dd5-b153-b5b755c27582)

**Далее Вам сгенерирует пароль, сохраняем его и нажимаем любую клавишу**

**Вписываем 1 и нажимаем Enter**

![Termius_M1TjKp7scM](https://github.com/user-attachments/assets/13a6c173-0adb-410c-8fd4-3be38022ed62)

**Создаем новый кошелек в Metamask и прописываем EVM адрес в терминале**

![Termius_yGD5jjKGQK](https://github.com/user-attachments/assets/c9623d4a-5f05-4050-84e4-a8982202c05d)

**Вводим еще раз этот же адрес**

![Termius_PeMqWvAh6J](https://github.com/user-attachments/assets/7a335c1e-02f0-4f20-a13f-78bc661b737c)

**Нажимаем любую клавишу**

![Termius_U83lnYLo83](https://github.com/user-attachments/assets/1be3356e-beb4-46f3-ab64-0ca5b61cb721)

На этом установка ноды окончена.

Вы можете использовать эту веб-страницу, чтобы застейкать свои токены и стать валидатором: https://staking.dill.xyz/.

Загрузите информацию о своем депозите 

Вы можете вставить содержимое файла deposit_data-xxx.json в поле ввода, затем нажмите кнопку "Продолжить", чтобы перейти к стейкингу.

![image](https://github.com/user-attachments/assets/e87a0bbc-be81-44ec-8209-0954e8fae8d4)

Для этого в терминале переходим в путь ``cd /root/dill/validator_keys/`` пишем ``ls`` далее видим файл deposit_data-xxx.json у Вас могут отличаться цифры. Нам нужно получить информацию с файла, пишем команду ``cat /root/dill/validator_keys/deposit_data-xxx.json`` вместо xxx пишем свои цифры файла.

Весь вывод файла копируем и вставляем на сайте. 

Если адрес кошелька, который Вы используете, совпадает с адресом вывода средств, вам нужно только нажать на флажок для подтверждения.

![image](https://github.com/user-attachments/assets/deaa7120-ec04-4648-924c-5d8daa77c4d7)

Перед выполнением не забудьте выполнить данный [квест](https://app.galxe.com/quest/Dill/GCgJAtvF1h?referral_code=GRFr2Jksp6m_3iKpJtsbLCqqHdfYUbQ694oJnZ9FPMaqhCt). Чтобы пополнить кошелек тестовыми токенами нужно выполнить данные задания и получить роль - https://discord.com/channels/1236933703251394570/1237043934870376468/1283351598835302410

После получения роли и запроса токенов на кошелек, выполняем транзакцию.

Просмотреть Вашего валидатора можно здесь - https://alps.dill.xyz/validators
