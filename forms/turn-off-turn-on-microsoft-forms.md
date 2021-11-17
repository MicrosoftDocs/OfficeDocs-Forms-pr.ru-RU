---
title: Включение и отключение Microsoft Forms
ms.author: jokay
author: dumptruckjon
manager: kathyl
audience: Admin
ms.topic: how-to
ms.service: forms-pro
ms.localizationpriority: high
description: В этой статье описывается, как администраторы Microsoft 365 могут отключать или включать Microsoft Forms для всей организации или определенных людей в своей организации.
ms.openlocfilehash: 2d1280bd7d61dc8b31cfb84dfeaced2662603e4f
ms.sourcegitcommit: 09bdc82ce67e74495b6c58d9c842e31c17956fc3
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 11/12/2021
ms.locfileid: "60951529"
---
# <a name="turn-off-or-turn-on-microsoft-forms"></a>Включение и отключение Microsoft Forms

По умолчанию служба [Microsoft Forms](https://support.microsoft.com/office/what-is-microsoft-forms-6b391205-523c-45d2-b53a-fc10b22017c8) включена для всех пользователей в организации. Если вы [администратор](https://support.microsoft.com/topic/eac4d046-1afd-4f1a-85fc-8219c79e1504), вы можете настроить [Microsoft Forms](https://support.microsoft.com/office/set-up-microsoft-forms-cc52287a-4550-464d-9a1b-457bf9df2240), а затем отключить эту службу или включить ее снова для всей вашей организации или только для отдельных пользователей.

## <a name="turn-off-microsoft-forms-for-everyone-in-your-organization"></a>Отключение Microsoft Forms для всех в вашей организации

1.  Войдите в [Microsoft Azure](https://portal.azure.com/).

2.  На левой панели выберите **Azure Active Directory**.

3.  Нажмите **Корпоративные приложения**.

4.  Перейдите к требуемым службам, а затем повторите шаги 5-7 для **Тип приложения**\> **CollabDBService** и **Приложения Майкрософт** \> **Microsoft Forms**.
    
      - В поле поиска в раскрывающемся списке **Тип приложения** введите **CollabDBService**. В списке результатов поиска выберите **CollabDBService**.
    
      - В раскрывающемся списке **Тип приложения** выберите **Приложения Майкрософт**. В поле поиска в раскрывающемся списке **Тип приложения** введите **Microsoft Forms** и в списке результатов поиска выберите **Microsoft Forms**.

5.  В разделе **Управление** выберите элемент **Свойства**.

6.  Для параметра **Включен ли вход для пользователей?** выберите **Нет**.

7.  Щелкните **Сохранить**.

## <a name="turn-off-microsoft-forms-for-specific-people-in-your-organization"></a>Отключение Microsoft Forms для отдельных пользователей в организации

1.  Войдите в Microsoft 365 как глобальный администратор под рабочей или учебной учетной записью. [Как выполнить вход](https://support.microsoft.com/office/where-to-sign-into-microsoft-365-for-business-e9eb7d51-5430-4929-91ab-6157c5a050b4).

2.  В Центре администрирования Microsoft 365 выберите **Пользователи** \> **Активные пользователи**.

3.  Установите флажок рядом с именем пользователя, для которого вы хотите отключить Microsoft Forms.

4.  На ленте нажмите кнопку **Управление лицензиями на продукты**.

5.  В открывшейся форме учетной записи на вкладке **Лицензии и приложения** разверните раздел "Приложения" и прокрутите его до пункта "Microsoft Forms". 

    :::image type="content" source="./media/turn-forms-off-on-licenses-apps.jpg" alt-text="Форма &quot;Параметры учетной записи&quot; в Центре администрирования Microsoft 365":::

6.  Снимите флажок, чтобы отключить Microsoft Forms. Чтобы включить Microsoft Forms, установите флажок.

    :::image type="content" source="./media/turn-forms-off-on-plan-e1.jpg" alt-text=" Переключатель &quot;Microsoft Forms&quot;":::

     > [!Note]
     > [Проверьте по этому списку](https://support.microsoft.com/office/office-licenses-that-include-microsoft-forms-efa14679-5d99-47c5-bdf1-2fc838767f7e), есть ли у вас лицензия Office, которая включает Microsoft Forms. Если ваша лицензия указана в списке, необходимо снять флажок "Microsoft Forms", чтобы полностью отключить доступ для пользователя.

7.  Внизу списка **Приложения** нажмите кнопку **Сохранить изменения**.

## <a name="i-turned-on-microsoft-forms-but-people-in-my-organization-still-cant-access-it"></a>После включения Microsoft Forms пользователи моей организации по-прежнему не имеют доступа.

Проверьте в Microsoft Azure следующую настройку, чтобы убедиться во включении Microsoft Forms:

1.  Войдите в [Microsoft Azure](https://portal.azure.com/).

2.  На левой панели выберите **Azure Active Directory**.

3.  Нажмите **Корпоративные приложения**.

4.  Перейдите к требуемым службам, а затем повторите шаги 5-7 для **Тип приложения**\> **CollabDBService** и **Приложения Майкрософт** \> **Microsoft Forms**.
    
      - В поле поиска в раскрывающемся списке **Тип приложения** введите **CollabDBService**. В списке результатов поиска выберите **CollabDBService**.
    
      - В раскрывающемся списке **Тип приложения** выберите **Приложения Майкрософт**. В поле поиска в раскрывающемся списке **Тип приложения** введите **Microsoft Forms** и в списке результатов поиска выберите **Microsoft Forms**.

5.  В разделе **Управление** выберите элемент **Свойства**.

6.  Для параметра **Включен ли вход для пользователей?** выберите **Да**.

7.  Щелкните **Сохранить**.

    >[!Note]
    >Чтобы сотрудники вашей организации имели доступ к Microsoft Forms, также необходимо включить Microsoft Windows SharePoint Services.

## <a name="feedback-for-microsoft-forms"></a>Отзывы о Microsoft Forms

Мы ждем ваших отзывов!\! Чтобы оставить отзыв о Microsoft Forms, в правом верхнем углу вашей формы выберите **Другие параметры формы** ![Дополнительные параметры](./media/image2.png)\> **Отзывы**.

