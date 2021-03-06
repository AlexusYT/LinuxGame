# LinuxGame
Еще одна попытка сделать игру, но уже под Linux

## История
* В 2016 году пробовал сделать 3D игру на Windows с использованием DirectX и WinAPI. 
* В 2017 году решил перевести разработку на Linux с использованием OpenGL.
* В течение следуюшего года-полтора занимался именно игрой, затем забросил

## Скриншоты и описание возможностей

Главное меню игры:
![image](https://user-images.githubusercontent.com/93870232/176842732-6c6ee186-fc32-4f65-a240-c8706daebe3b.png)

Задний фон был выбран случайно, с недавней поездки. Оформление не было главной задачей

Игровой мир:
![image](https://user-images.githubusercontent.com/93870232/176844404-dbb92755-3ee8-46eb-9686-bb01bde72855.png)

На скриншоте видно полное отсутвие освещения, шейдеров и прочих элементов, необходимых для любой игры. Также в игре полное отстутвие оптимзации. 10-15 деревьев просаживают FPS до 10. Но несмотря на это, в игре есть несколько механик. 

Например если подойти к дереву, нажать ПКМ и подождать некоторое время, дерево начнет разбираться на лозу и палки. Эти ресурсы нужны для сооружения некоторыз построек. Например майнер руд:

![image](https://user-images.githubusercontent.com/93870232/178134958-68887c73-92ab-42bc-8b3a-6ede35b755e0.png)

Размещаем его на поверхности

![image](https://user-images.githubusercontent.com/93870232/178135026-f0aa5187-7c56-4750-8996-9e0429b71d00.png)

После завершения постройки конструкции, можно навести на него курсор и нажать "E", откроется инвентарь:

![image](https://user-images.githubusercontent.com/93870232/178135111-799a37e4-bc08-48ef-8f59-0e28978831b2.png)

Далее в него необходимо положить вал и добывающее колесо. После этого в инвентаре начинает отображаться текущее состояние постройки:

![image](https://user-images.githubusercontent.com/93870232/178135220-eee475ec-f127-4c96-ad99-5d8c3a56091e.png)

Так как сооружение требует для своей работы вращение, состояние отображает информацию о скорости, крутящем моменте и мощности. Значения указаны случайно на время тестирования.

## Планы на будущее
* собрать команду и продолжить разработку
