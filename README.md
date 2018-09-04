<configuration>
<params>
<param name="Loyalty" description="Программа лояльности «Спасибо от Сбербанка»">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="mobile.sberbank.ru" description="Стенд ПСИ">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<offers>true</offers>
<charity>false</charity>
<charityPLSpasibo>true</charityPLSpasibo>
<beforelogin>true</beforelogin>
</node>
<node id="node0.online.sberbank.ru">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<offers>true</offers>
<charity>false</charity>
<charityPLSpasibo>true</charityPLSpasibo>
<beforelogin>true</beforelogin>
</node>
<node id="node1.online.sberbank.ru">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<offers>true</offers>
<charity>false</charity>
<charityPLSpasibo>true</charityPLSpasibo>
<beforelogin>true</beforelogin>
</node>
<node id="node2.online.sberbank.ru">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<offers>true</offers>
<charity>false</charity>
<charityPLSpasibo>true</charityPLSpasibo>
<beforelogin>true</beforelogin>
</node>
<node id="node3.online.sberbank.ru">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<offers>true</offers>
<charity>false</charity>
<charityPLSpasibo>true</charityPLSpasibo>
<beforelogin>true</beforelogin>
</node>
<node id="node4.online.sberbank.ru">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<offers>true</offers>
<charity>false</charity>
<charityPLSpasibo>true</charityPLSpasibo>
<beforelogin>true</beforelogin>
</node>
<node id="greenfield1.online.sberbank.ru">
<bonusBalance>true</bonusBalance>
<dashboard>true</dashboard>
<distanceToNearestSalesPoint>true</distanceToNearestSalesPoint>
<offers>true</offers>
<charity>false</charity>
<charityPLSpasibo>true</charityPLSpasibo>
<beforelogin>true</beforelogin>
</node>
</nodes>
</param>
<param name="LoyaltyPreloginZone" description="Прелогин зона Спасибо">
<type>list</type>
<enabled>true</enabled>
</param>
<param name="DebitCardAppMP" description="Заказ дебетовых карт">
<type>service</type>
<enabled>true</enabled>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>true</ikaotransliteration>
<apiv2>true</apiv2>
<api_urls>
<api_url name="searchBranches_v1" url="/card/v1/mobile/rest/searchBranches"/>
<api_url name="searchBranches_v2" url="/card/v2/mobile/rest/searchBranches"/>
<api_url name="init_v1" url="/card/v1/mobile/rest/init"/>
<api_url name="init_v2" url="/card/v2/mobile/rest/init"/>
<api_url name="create_v1" url="/card/v1/mobile/rest/create"/>
<api_url name="create_v2" url="/card/v2/mobile/rest/create"/>
<api_url name="send_v1" url="/card/v1/mobile/rest/send"/>
<api_url name="send_v2" url="/card/v2/mobile/rest/send"/>
<api_url name="operationHistory_v1" url="/card/v1/mobile/rest/OperationHistory"/>
<api_url name="operationHistory_v2" url="/card/v2/mobile/rest/OperationHistory"/>
<api_url name="countries_v1" url="/card/v1/mobile/rest/countries"/>
<api_url name="countries_v2" url="/card/v2/mobile/rest/countries"/>
</api_urls>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>false</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>false</apiv2>
</node>
<node id="node1.online.sberbank.ru">
<enabled>false</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>false</ufsbranches>
<ufshistory>false</ufshistory>
<digitalcardshow>false</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>false</apiv2>
</node>
<node id="node2.online.sberbank.ru">
<enabled>false</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>false</ufsbranches>
<ufshistory>false</ufshistory>
<digitalcardshow>false</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>false</apiv2>
</node>
<node id="node3.online.sberbank.ru">
<enabled>false</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>false</ufsbranches>
<ufshistory>false</ufshistory>
<digitalcardshow>false</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>false</apiv2>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>false</apiv2>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>true</apiv2>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>true</apiv2>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>true</apiv2>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>true</apiv2>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>true</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>true</apiv2>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>false</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>true</apiv2>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>false</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>true</apiv2>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<ufsbranches>true</ufsbranches>
<ufshistory>true</ufshistory>
<digitalcardshow>false</digitalcardshow>
<ikaotransliteration>false</ikaotransliteration>
<apiv2>true</apiv2>
</node>
</nodes>
</param>
<param name="DigitalCardAppMP" description="Заказ цифровых карт">
<type>service</type>
<enabled>true</enabled>
<embossingtitle>Имя владельца</embossingtitle>
<embossingvalue>DIGITAL CARD</embossingvalue>
<embossingdescription>Это поле может пригодится для оплаты в интернете</embossingdescription>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>false</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<embossingenabled>false</embossingenabled>
<showhints>true</showhints>
</node>
<node id="node1.online.sberbank.ru">
<enabled>false</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<embossingenabled>false</embossingenabled>
<showhints>true</showhints>
</node>
<node id="node2.online.sberbank.ru">
<enabled>false</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<embossingenabled>false</embossingenabled>
<showhints>true</showhints>
</node>
<node id="node3.online.sberbank.ru">
<enabled>false</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<embossingenabled>false</embossingenabled>
<showhints>true</showhints>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<showhints>true</showhints>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<panrq>true</panrq>
<showhints>true</showhints>
</node>
<node id="ift-node0.testonline.sberbank.ru">
<enabled>false</enabled>
<fatkashow>false</fatkashow>
<getcvv>false</getcvv>
<ufshistory>false</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<panrq>true</panrq>
<showhints>true</showhints>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<panrq>true</panrq>
<showhints>true</showhints>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<panrq>true</panrq>
<showhints>true</showhints>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<panrq>true</panrq>
<showhints>true</showhints>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<blocknotification>true</blocknotification>
<embossingenabled>true</embossingenabled>
<panrq>true</panrq>
<showhints>true</showhints>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<fatkashow>false</fatkashow>
<getcvv>true</getcvv>
<ufshistory>true</ufshistory>
<embossingenabled>true</embossingenabled>
</node>
</nodes>
</param>
<param name="CardCVV" description="Определение типов карт для запроса CVV">
<type>list</type>
<enabled>true</enabled>
<key>name</key>
<cardCvvList>
<cardCvv id="Visa Digital"/>
</cardCvvList>
</param>
<param name="BlockingNotification" description="Карты с выводом нотификации при блокировке">
<type>service</type>
<cardBlockList>
<cardBlock id="Visa Digital"/>
</cardBlockList>
<notification>
<title>Перевести остаток средств перед блокировкой?</title>
<description>
Рекомендуем перед блокировкой карты перевести остаток средств на другую карту или счет. После блокировки карты получить денежные средства можно будет только в офисе банка при предъявлении документа, удостоверяющего личность
</description>
<buttontextcontinue>Продолжить</buttontextcontinue>
<buttontexttransfer>Перевести</buttontexttransfer>
</notification>
<reasonList>
<reason id="other"/>
</reasonList>
</param>
<param name="CardPANRq" description="Определение типов карт для запроса PAN-номера карты">
<type>list</type>
<enabled>true</enabled>
<key>name</key>
<CardPANRqList>
<CardPANRq id="Visa Digital"/>
</CardPANRqList>
</param>
<param name="pin_number" description="">
<type>setting</type>
<enabled>true</enabled>
<number>320</number>
</param>
<param name="alf" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="uak" description="">
<type>setting</type>
<enabled>true</enabled>
<syncContacts>true</syncContacts>
</param>
<param name="avatar" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="rating" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="standin" description="">
<type>setting</type>
<enabled>false</enabled>
<host>node0.online.sberbank.ru</host>
</param>
<param name="gamification" description="">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="aeroexpress" description="">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="statement" description="Выписка по истории операций">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<cardStatement>false</cardStatement>
<viewerStatement>false</viewerStatement>
</node>
<node id="node1.online.sberbank.ru">
<cardStatement>false</cardStatement>
<viewerStatement>false</viewerStatement>
</node>
<node id="node2.online.sberbank.ru">
<cardStatement>false</cardStatement>
<viewerStatement>false</viewerStatement>
</node>
<node id="node3.online.sberbank.ru">
<cardStatement>false</cardStatement>
<viewerStatement>false</viewerStatement>
</node>
<node id="greenfield1.online.sberbank.ru">
<cardStatement>false</cardStatement>
<viewerStatement>false</viewerStatement>
</node>
<node id="greenfield1.online.sberbank.ru">
<cardStatement>false</cardStatement>
<viewerStatement>false</viewerStatement>
</node>
<node id="greenfield1.online.sberbank.ru">
<cardStatement>false</cardStatement>
<viewerStatement>false</viewerStatement>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<cardStatement>true</cardStatement>
<viewerStatement>true</viewerStatement>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<cardStatement>true</cardStatement>
<viewerStatement>true</viewerStatement>
</node>
<node id="mobile.sberbank.ru">
<cardStatement>true</cardStatement>
<viewerStatement>true</viewerStatement>
</node>
</nodes>
</param>
<param name="VMT" description="VISA MoneyTransfer">
<type>limit</type>
<enabled>true</enabled>
<minamount>1</minamount>
<maxamount>30000</maxamount>
<cumulative>30000</cumulative>
<currency>RUB</currency>
</param>
<param name="MCMS" description="MasterCard MoneySend">
<type>limit</type>
<enabled>true</enabled>
<minamount>1</minamount>
<maxamount>30000</maxamount>
<cumulative>150000</cumulative>
<currency>RUB</currency>
</param>
<param name="tarifPlanParams" description="">
<type>list</type>
<enabled>true</enabled>
<tarifPlans>
<tarifPlan id="0">
<phoneNumbers>
<phoneNumber cntr="ru" prior="1" addInfo="По России бесплатно (МТС, Билайн, Мегафон, Tele2, Yota, Мотив)" pin="99">900</phoneNumber>
<phoneNumber cntr="other" prior="2" addInfo="Из-за границы по тарифу оператора" pin="99">+7 495 500-55-50</phoneNumber>
</phoneNumbers>
</tarifPlan>
<tarifPlan id="1">
<phoneNumbers>
<phoneNumber cntr="ru" prior="1" addInfo="По России бесплатно" pin="0">8-800-555-02-55</phoneNumber>
<phoneNumber cntr="other" prior="2" addInfo="Из-за границы по тарифу оператора" pin="0">+7 495 669-06-38</phoneNumber>
</phoneNumbers>
</tarifPlan>
<tarifPlan id="2">
<phoneNumbers>
<phoneNumber cntr="ru" prior="1" addInfo="По России бесплатно (МТС, Билайн, Мегафон, Tele2, Yota, Мотив)" pin="99">900</phoneNumber>
<phoneNumber cntr="other" prior="2" addInfo="Из-за границы по тарифу оператора" pin="99">+7 495 500-55-50</phoneNumber>
</phoneNumbers>
</tarifPlan>
<tarifPlan id="3">
<phoneNumbers>
<phoneNumber cntr="ru" prior="1" addInfo="По России бесплатно" pin="0">8-800-333-22-33</phoneNumber>
<phoneNumber cntr="other" prior="2" addInfo="Из-за границы по тарифу оператора" pin="0">+7 495 544-45-40</phoneNumber>
</phoneNumbers>
</tarifPlan>
</tarifPlans>
</param>
<param name="newVersion" description="">
<type>setting</type>
<enabled>true</enabled>
<newVersion>7.6.1</newVersion>
</param>
<param name="scan_period" description="">
<type>setting</type>
<enabled>true</enabled>
<scan_period>7</scan_period>
</param>
<param name="Manual" description="Руководство пользователя">
<type>link</type>
<link>
http://www.sberbank.ru/common/img/uploaded/files/pdf/Manual_Android.pdf
</link>
</param>
<param name="craudgifting" description="switch for craudgifting">
<type>setting</type>
<languages localeId="ru" enabled="true"/>
<languages localeId="en" enabled="false"/>
<receivers>15</receivers>
</param>
<param name="moneybox" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="self_registration_translate" description="Замена строк при саморегистрации если локализация отлична от дефолтной">
<type>strings</type>
<strings>
<string>
<RU>попытки</RU>
<EN>attempts</EN>
</string>
<string>
<RU>
Пароль не должен повторять старые пароли за последние 3 месяца
</RU>
<EN>
The password must not repeat the old passwords in the last 3 months
</EN>
</string>
<string>
<RU>
Введенный идентификатор уже используется в системе. Введите другое значение
</RU>
<EN>
The entered ID is already in use in the system. Enter a different value
</EN>
</string>
</strings>
</param>
<param name="fundInfo" description="Получение информации о наличии у контактов МП про-версии">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="wrongpass" description="">
<type>list</type>
<enabled>true</enabled>
<attempts>
<attempt>
<localeId>ru</localeId>
<count>1</count>
<string>
Вы неверно ввели код 1 раз. Если вы 3 раза введете код неверно, вы будете заблокированы на 1 час
</string>
</attempt>
<attempt>
<localeId>ru</localeId>
<count>2</count>
<string>
Вы неверно ввели код 2 раза. У вас осталась 1 попытка. Если вы забыли код на вход, воспользуйтесь функцией «забыл код на вход».
</string>
</attempt>
</attempts>
</param>
<param name="marketplaceMainScreenOffer" description="Промо-блок банковских продуктов и точка входа на витрину на главном экране МП">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="newmarketplace" description="Витрина 7.3.1">
<type>setting</type>
<enabled>true</enabled>
<urls>
<url name="marketplace_v1" url="https://test.stat.online.sberbank.ru/PhizIC-res/mapicfg/marketplace/config.android.7.7.xml" version="7.11"/>
<url name="marketplace_v2" url="https://test.stat.online.sberbank.ru/PhizIC-res/mapicfg/marketplace/config.android.7.11.xml" version="7.11"/>
<url name="marketplace_v2" url="https://test.stat.online.sberbank.ru/PhizIC-res/mapicfg/marketplace/config.android.8.0.xml" version="8.0"/>
<url name="marketplace_v2" url="https://test.stat.online.sberbank.ru/PhizIC-res/mapicfg/marketplace/config.android.8.1.xml" version="8.1"/>
<url name="marketplace_v2" url="https://test.stat.online.sberbank.ru/PhizIC-res/mapicfg/marketplace/config.android.8.2.xml" version="8.2"/>
<url name="marketplace_v2" url="https://test.stat.online.sberbank.ru/PhizIC-res/mapicfg/marketplace/config.android.8.4.xml" version="8.4"/>
</urls>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="node4.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="194.186.207.23">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="mobile.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled_Marketplace_2_0>true</enabled_Marketplace_2_0>
<mainEntryEnabled>true</mainEntryEnabled>
<allProductsEnabled>true</allProductsEnabled>
<personalizationEnabled>true</personalizationEnabled>
</node>
</nodes>
</param>
<param name="marketplace_search_ignore" description="Не отображение в поиске определенных поставщиков услуг">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="pushErib" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="pushErib75" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="birthday" description="">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="aim_status" description="Индикация выполнения цели">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="aim_share" description="Шаринг цели">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="local_tips" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="PFMPermissions-76" description="false - МП реагирует на permissions.do">
<type>list</type>
<enabled>false</enabled>
<nodes> </nodes>
</param>
<param name="PFMConfigFlags" description="Блоки работают по логическому ИЛИ">
<PfmGlobal> </PfmGlobal>
<PfmNodes>
<node id="node0.online.sberbank.ru">
<PFMSimilarSpendings>false</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.00</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<pfmApiVersion>1.30</pfmApiVersion>
<minAppVersionFromPFMApiVersion>8.0.0</minAppVersionFromPFMApiVersion>
<Budget3.0Enabled>false</Budget3.0Enabled>
<pfmDataOnline>false</pfmDataOnline>
<BudgetOnMyFinance>true</BudgetOnMyFinance>
</node>
<node id="node1.online.sberbank.ru">
<PFMSimilarSpendings>false</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.00</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<pfmApiVersion>1.30</pfmApiVersion>
<minAppVersionFromPFMApiVersion>8.0.0</minAppVersionFromPFMApiVersion>
<Budget3.0Enabled>false</Budget3.0Enabled>
<pfmDataOnline>false</pfmDataOnline>
<BudgetOnMyFinance>true</BudgetOnMyFinance>
</node>
<node id="node2.online.sberbank.ru">
<PFMSimilarSpendings>false</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.00</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<pfmApiVersion>1.30</pfmApiVersion>
<minAppVersionFromPFMApiVersion>8.0.0</minAppVersionFromPFMApiVersion>
<Budget3.0Enabled>false</Budget3.0Enabled>
<pfmDataOnline>false</pfmDataOnline>
<BudgetOnMyFinance>true</BudgetOnMyFinance>
</node>
<node id="node3.online.sberbank.ru">
<PFMSimilarSpendings>false</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.00</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<pfmApiVersion>1.30</pfmApiVersion>
<minAppVersionFromPFMApiVersion>8.0.0</minAppVersionFromPFMApiVersion>
<Budget3.0Enabled>false</Budget3.0Enabled>
<pfmDataOnline>false</pfmDataOnline>
<BudgetOnMyFinance>true</BudgetOnMyFinance>
</node>
<node id="greenfield1.online.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.00</currentPfmApiVersion>
<PFMUserParams>true</PFMUserParams>
<PFMOfferTips>false</PFMOfferTips>
<pfmApiVersion>1.30</pfmApiVersion>
<minAppVersionFromPFMApiVersion>8.0.0</minAppVersionFromPFMApiVersion>
<Budget3.0Enabled>true</Budget3.0Enabled>
<pfmDataOnline>false</pfmDataOnline>
<BudgetOnMyFinance>true</BudgetOnMyFinance>
</node>
<node id="194.186.207.23">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.00</currentPfmApiVersion>
<PFMUserParams>true</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.30</pfmApiVersion>
<minAppVersionFromPFMApiVersion>8.0.0</minAppVersionFromPFMApiVersion>
<Budget3.0Enabled>false</Budget3.0Enabled>
<pfmDataOnline>false</pfmDataOnline>
<BudgetOnMyFinance>true</BudgetOnMyFinance>
</node>
<node id="mobile.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.20</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.30</pfmApiVersion>
<minAppVersionFromPFMApiVersion>8.0.0</minAppVersionFromPFMApiVersion>
<Budget3.0Enabled>false</Budget3.0Enabled>
<pfmDataOnline>false</pfmDataOnline>
<BudgetOnMyFinance>true</BudgetOnMyFinance>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.20</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.30</pfmApiVersion>
<minAppVersionFromPFMApiVersion>8.0.0</minAppVersionFromPFMApiVersion>
<Budget3.0Enabled>true</Budget3.0Enabled>
<pfmDataOnline>false</pfmDataOnline>
<BudgetOnMyFinance>true</BudgetOnMyFinance>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.20</currentPfmApiVersion>
<PFMUserParams>true</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.30</pfmApiVersion>
<minAppVersionFromPFMApiVersion>8.0.0</minAppVersionFromPFMApiVersion>
<Budget3.0Enabled>true</Budget3.0Enabled>
<pfmDataOnline>false</pfmDataOnline>
<BudgetOnMyFinance>true</BudgetOnMyFinance>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<PFMSimilarSpendings>true</PFMSimilarSpendings>
<currentPfmApiVersion description="Устаревший параметр">1.20</currentPfmApiVersion>
<PFMUserParams>false</PFMUserParams>
<PFMOfferTips>true</PFMOfferTips>
<pfmApiVersion>1.30</pfmApiVersion>
<minAppVersionFromPFMApiVersion>8.0.0</minAppVersionFromPFMApiVersion>
<Budget3.0Enabled>true</Budget3.0Enabled>
<pfmDataOnline>false</pfmDataOnline>
<BudgetOnMyFinance>true</BudgetOnMyFinance>
</node>
</PfmNodes>
</param>
<param name="pfmHosts" description="Список хостов для phizPFM">
<type>list</type>
<enabled>true</enabled>
<hosts>
<host id="node0.online.sberbank.ru">
<value>pfm.node0.online.sberbank.ru:4433</value>
</host>
<host id="node1.online.sberbank.ru">
<value>pfm.node1.online.sberbank.ru:4433</value>
</host>
<host id="node2.online.sberbank.ru">
<value>pfm.node2.online.sberbank.ru:4433</value>
</host>
<host id="node3.online.sberbank.ru">
<value>pfm.node3.online.sberbank.ru:4433</value>
</host>
<host id="greenfield1.online.sberbank.ru">
<value>greenfield1.online.sberbank.ru:6655</value>
</host>
<host id="194.186.207.23">
<value>194.186.207.23</value>
</host>
<host id="mobile.sberbank.ru">
<value>mobile.sberbank.ru</value>
</host>
</hosts>
</param>
<param name="PFMDashboardIncomeHide" description="Дашбоард, доходы, скрытие АЛФ операций">
<type>list</type>
<enabled>true</enabled>
<PfmNodes>
<node id="node0.online.sberbank.ru">
<dashboard-76>true</dashboard-76>
<income>false</income>
<hidealfoperations>false</hidealfoperations>
<renameRecognizedOperations>false</renameRecognizedOperations>
</node>
<node id="node1.online.sberbank.ru">
<dashboard-76>true</dashboard-76>
<income>false</income>
<hidealfoperations>false</hidealfoperations>
<renameRecognizedOperations>false</renameRecognizedOperations>
</node>
<node id="node2.online.sberbank.ru">
<dashboard-76>true</dashboard-76>
<income>false</income>
<hidealfoperations>false</hidealfoperations>
<renameRecognizedOperations>false</renameRecognizedOperations>
</node>
<node id="node3.online.sberbank.ru">
<dashboard-76>true</dashboard-76>
<income>false</income>
<hidealfoperations>false</hidealfoperations>
<renameRecognizedOperations>false</renameRecognizedOperations>
</node>
<node id="greenfield1.online.sberbank.ru">
<dashboard-76>true</dashboard-76>
<income>true</income>
<hidealfoperations>true</hidealfoperations>
<renameRecognizedOperations>false</renameRecognizedOperations>
</node>
<node id="194.186.207.23">
<dashboard-76>true</dashboard-76>
<income>true</income>
<hidealfoperations>true</hidealfoperations>
<renameRecognizedOperations>true</renameRecognizedOperations>
</node>
<node id="mobile.sberbank.ru">
<dashboard-76>true</dashboard-76>
<income>true</income>
<hidealfoperations>true</hidealfoperations>
<renameRecognizedOperations>true</renameRecognizedOperations>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<dashboard-76>true</dashboard-76>
<income>true</income>
<hidealfoperations>true</hidealfoperations>
<renameRecognizedOperations>true</renameRecognizedOperations>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<dashboard-76>true</dashboard-76>
<income>true</income>
<hidealfoperations>true</hidealfoperations>
<renameRecognizedOperations>true</renameRecognizedOperations>
</node>
<node id="sbt-oafs-703.sigma.sbrf.ru">
<dashboard-76>true</dashboard-76>
<income>true</income>
<hidealfoperations>true</hidealfoperations>
<renameRecognizedOperations>true</renameRecognizedOperations>
</node>
</PfmNodes>
</param>
<param name="PFMTipsCloseEmptyQuizCount" description="Вероятность, с которой пользователю будет предложено выбрать причину скрытия совета">
<type>setting</type>
<enabled>false</enabled>
<value>0.25</value>
</param>
<param name="PushPlatformID" description="URL серверов Push-платформы">
<type>setting</type>
<enabled>true</enabled>
<platforms>
<platform id="1" url="http://pushservertest.mfms.ru/push-test"/>
<platform id="3" url="https://pushserver.mfms.ru/sbrf"/>
<platform id="4" url="https://pushserver.sberbank-tele.com"/>
<platform id="5" url="https://pushserver-test.sberbank-tele.com"/>
</platforms>
</param>
<param name="LawUrlsID" description="URL юридических документов в формате html">
<type>setting</type>
<enabled>true</enabled>
<lawUrls>
<lawUrl name="privacyPolicy" title="Политика конфиденциальности" url="https://en.wikipedia.org/wiki/Confidentiality"/>
<lawUrl name="userAgreement" title="Пользовательское соглашение" url="https://en.wikipedia.org/wiki/User_(computing)"/>
</lawUrls>
</param>
<param name="invoicing" description="Инвойсинг версия 7.6">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="prelogin_DebitCardOffer" description="">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="login_DebitCardOffer" description="">
<type>setting</type>
<enabled>false</enabled>
</param>
<param description="Кошелёк" name="Wallet">
<type>list</type>
<enabled>true</enabled>
<host>https://geo2.online.sberbank.ru:4488</host>
<usescenario>true</usescenario>
<autorization_delay>100</autorization_delay>
<additionalConfirm>false</additionalConfirm>
<nodes>
<node id="greenfield1.online.sberbank.ru" blockName="greenfield1">
<enabled>true</enabled>
</node>
<node id="194.186.207.23" blockName="psi">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru" blockName="newpsi">
<enabled>true</enabled>
</node>
<node id="node0.online.sberbank.ru" blockName="node0">
<enabled>false</enabled>
</node>
<node id="node1.online.sberbank.ru" blockName="node1">
<enabled>false</enabled>
</node>
<node id="node2.online.sberbank.ru" blockName="node2">
<enabled>false</enabled>
</node>
<node id="node3.online.sberbank.ru" blockName="node3">
<enabled>false</enabled>
</node>
</nodes>
</param>
<param description="Текстовый_чат" name="VOTCH">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="VOIPCallOperator" description="Звонок оператору через интернет">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabledNotAuthenticated>false</enabledNotAuthenticated>
<enabledSideBar>false</enabledSideBar>
<enabledInChat>false</enabledInChat>
<enabledInClientManager>true</enabledInClientManager>
<enabledInSberChatProfile>true</enabledInSberChatProfile>
<sessionHandlingEnabled>true</sessionHandlingEnabled>
<tutorialIpCallEnabled>true</tutorialIpCallEnabled>
</node>
<node id="node1.online.sberbank.ru">
<enabledNotAuthenticated>false</enabledNotAuthenticated>
<enabledSideBar>false</enabledSideBar>
<enabledInChat>false</enabledInChat>
<enabledInClientManager>true</enabledInClientManager>
<enabledInSberChatProfile>true</enabledInSberChatProfile>
<sessionHandlingEnabled>true</sessionHandlingEnabled>
<tutorialIpCallEnabled>true</tutorialIpCallEnabled>
</node>
<node id="node2.online.sberbank.ru">
<enabledNotAuthenticated>false</enabledNotAuthenticated>
<enabledSideBar>false</enabledSideBar>
<enabledInChat>false</enabledInChat>
<enabledInClientManager>true</enabledInClientManager>
<enabledInSberChatProfile>true</enabledInSberChatProfile>
<sessionHandlingEnabled>true</sessionHandlingEnabled>
<tutorialIpCallEnabled>true</tutorialIpCallEnabled>
</node>
<node id="node3.online.sberbank.ru">
<enabledNotAuthenticated>false</enabledNotAuthenticated>
<enabledSideBar>false</enabledSideBar>
<enabledInChat>false</enabledInChat>
<enabledInClientManager>true</enabledInClientManager>
<enabledInSberChatProfile>true</enabledInSberChatProfile>
<sessionHandlingEnabled>true</sessionHandlingEnabled>
<tutorialIpCallEnabled>true</tutorialIpCallEnabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabledNotAuthenticated>true</enabledNotAuthenticated>
<enabledSideBar>true</enabledSideBar>
<enabledInChat>true</enabledInChat>
<enabledInClientManager>true</enabledInClientManager>
<enabledInSberChatProfile>true</enabledInSberChatProfile>
<sessionHandlingEnabled>true</sessionHandlingEnabled>
<tutorialIpCallEnabled>true</tutorialIpCallEnabled>
</node>
<node id="194.186.207.23">
<enabledNotAuthenticated>false</enabledNotAuthenticated>
<enabledSideBar>false</enabledSideBar>
<enabledInChat>false</enabledInChat>
<enabledInClientManager>true</enabledInClientManager>
<enabledInSberChatProfile>true</enabledInSberChatProfile>
<sessionHandlingEnabled>true</sessionHandlingEnabled>
<tutorialIpCallEnabled>true</tutorialIpCallEnabled>
</node>
<node id="mobile.sberbank.ru">
<enabledNotAuthenticated>true</enabledNotAuthenticated>
<enabledSideBar>true</enabledSideBar>
<enabledInChat>true</enabledInChat>
<enabledInClientManager>true</enabledInClientManager>
<enabledInSberChatProfile>true</enabledInSberChatProfile>
<sessionHandlingEnabled>true</sessionHandlingEnabled>
<tutorialIpCallEnabled>true</tutorialIpCallEnabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabledNotAuthenticated>true</enabledNotAuthenticated>
<enabledSideBar>true</enabledSideBar>
<enabledInChat>true</enabledInChat>
<enabledInClientManager>true</enabledInClientManager>
<enabledInSberChatProfile>true</enabledInSberChatProfile>
<sessionHandlingEnabled>true</sessionHandlingEnabled>
<tutorialIpCallEnabled>true</tutorialIpCallEnabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabledNotAuthenticated>true</enabledNotAuthenticated>
<enabledSideBar>true</enabledSideBar>
<enabledInChat>true</enabledInChat>
<enabledInClientManager>true</enabledInClientManager>
<enabledInSberChatProfile>true</enabledInSberChatProfile>
<sessionHandlingEnabled>true</sessionHandlingEnabled>
<tutorialIpCallEnabled>true</tutorialIpCallEnabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabledNotAuthenticated>true</enabledNotAuthenticated>
<enabledSideBar>true</enabledSideBar>
<enabledInChat>true</enabledInChat>
<enabledInClientManager>true</enabledInClientManager>
<enabledInSberChatProfile>true</enabledInSberChatProfile>
<sessionHandlingEnabled>true</sessionHandlingEnabled>
<tutorialIpCallEnabled>true</tutorialIpCallEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabledNotAuthenticated>true</enabledNotAuthenticated>
<enabledSideBar>true</enabledSideBar>
<enabledInChat>true</enabledInChat>
<enabledInClientManager>true</enabledInClientManager>
<enabledInSberChatProfile>true</enabledInSberChatProfile>
<sessionHandlingEnabled>true</sessionHandlingEnabled>
<tutorialIpCallEnabled>true</tutorialIpCallEnabled>
</node>
</nodes>
</param>
<param name="aim_close" description="Закрытие Цели">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="AlertMessage_7_11_3" description="Информационный баннер на Главном экране">
<enabled>true</enabled>
<importantInfo>
<messageType>message</messageType>
<startDate>10.05.2018 00:00:00 +0300</startDate>
<endDate>10.05.2018 23:59:59 +0300</endDate>
<colorTitle>#ffb74e</colorTitle>
<colorShortText>#FFFBF6</colorShortText>
<colorText>#000000</colorText>
<title>С Днем Великой Победы</title>
<shortText>Герои живы, пока жива наша память о них.</shortText>
<longText>
9 мая мы будем вспоминать о великом подвиге нашего народа, о силе духа и любви к Родине. Пусть эти вечные ценности живут в душах новых поколений, а салют в честь Великой Победы наполняет сердца радостью и гордостью за героев, которые защитили родную землю! Желаем Вам, Вашим семьям, Вашим близким мирного неба над головой, благополучия и добра! Для Вас мы подготовили видеоролик. Посмотреть на [www.sberbank.ru](http://www.sberbank.ru/9may_2018)
</longText>
<buttonName>Подробнее</buttonName>
</importantInfo>
</param>
<param name="AlertMessage" description="Сообщение о недоступности некоторых сервисов">
<importantInfo>
<endDate>30.04.2018 00:00:00 +0300</endDate>
<title>Важное сообщение</title>
<shortText>
Технологические работы и ограничения в период с 28 по 30 апреля 2018 года
</shortText>
<longText>
<![CDATA[
С 28 апреля по 30 апреля мы проводим технологические работы по преобразованию региональной сети банка, в связи с чем в Сбербанк Онлайн будут действовать ограничения: · 28 апреля с 22:00 до 01:00 29 апреля по московскому времени недоступны операции по счетам (вклады, металлические счета): переводы между счетами, валютно-обменные операции, формирование выписок; · 29 апреля с 01:00 до 07:00 по московскому времени Сбербанк Онлайн будет полностью недоступен (невозможен вход); · 29 апреля с 07:00 до 14:00 по московскому времени недоступны: история операций, диалоги, работа с ранее созданными шаблонами и интернет-заказами, ранее установленные настройки профиля; · 29 апреля с 07:00 до 04:00 30 апреля по московскому времени сумма полной задолженности по кредиту будет актуальна на дату предыдущего входа в Сбербанк Онлайн. Подробнее с информацией о влиянии работ по преобразованию региональной сети банка вы можете ознакомиться на [www.sberbank.ru](http://www.sberbank.ru/techbreak) или позвонив по бесплатному номеру 8 800 100-74-05.
]]>
</longText>
</importantInfo>
</param>
<param name="CorePermissions" description="Консолидированные включатели функционала Core APP">
<type>list</type>
<enabled>true</enabled>
<mAPI>9.2</mAPI>
<nodes>
<node id="node0.online.sberbank.ru">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>false</SBTelecom>
<CreditRating>false</CreditRating>
<OKBRating>false</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>true</creditCardArrears>
<Spasibo>true</Spasibo>
<autoTransfers_7_10>true</autoTransfers_7_10>
<pciDss>true</pciDss>
<creditCardAutorepayment>false</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost>true</UFSHost>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>false</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>true</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>false</blockedCardsStatusWay4>
<enableContactManager>false</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>true</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
<node id="node1.online.sberbank.ru">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>false</SBTelecom>
<CreditRating>false</CreditRating>
<OKBRating>false</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>true</creditCardArrears>
<Spasibo>true</Spasibo>
<autoTransfers_7_10>true</autoTransfers_7_10>
<pciDss>true</pciDss>
<creditCardAutorepayment>false</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost/>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>false</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>true</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>false</blockedCardsStatusWay4>
<enableContactManager>false</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<charity>
<enabled>true</enabled>
<billing>284</billing>
<provider>621180</provider>
<service>297</service>
<text>пострадавшим в Кемерове</text>
</charity>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>true</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
<node id="node2.online.sberbank.ru">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>false</SBTelecom>
<CreditRating>false</CreditRating>
<OKBRating>false</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>true</creditCardArrears>
<autoTransfers_7_10>true</autoTransfers_7_10>
<Spasibo>true</Spasibo>
<pciDss>true</pciDss>
<creditCardAutorepayment>false</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost/>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>false</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>true</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>false</blockedCardsStatusWay4>
<enableContactManager>false</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<charity>
<enabled>true</enabled>
<billing>284</billing>
<provider>500438244</provider>
<service>297</service>
<text>пострадавшим в Кемеровской области</text>
</charity>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>true</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
<node id="node3.online.sberbank.ru">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>false</SBTelecom>
<CreditRating>false</CreditRating>
<OKBRating>false</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>true</creditCardArrears>
<Spasibo>true</Spasibo>
<autoTransfers_7_10>true</autoTransfers_7_10>
<pciDss>true</pciDss>
<creditCardAutorepayment>false</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost/>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>false</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>true</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>false</blockedCardsStatusWay4>
<enableContactManager>false</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<charity>
<enabled>true</enabled>
<billing>284</billing>
<provider>500437522</provider>
<service>297</service>
<text>пострадавшим в Кемерове</text>
</charity>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>true</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
<node id="greenfield1.online.sberbank.ru">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>false</SBTelecom>
<CreditRating>true</CreditRating>
<OKBRating>false</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>true</creditCardArrears>
<Spasibo>true</Spasibo>
<autoTransfers_7_10>true</autoTransfers_7_10>
<pciDss>true</pciDss>
<creditCardAutorepayment>false</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost/>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showAllHistoryOperations>true</showAllHistoryOperations>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>true</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>false</blockedCardsStatusWay4>
<enableContactManager>false</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<charity>
<enabled>true</enabled>
<billing>284</billing>
<provider>550470225</provider>
<service>297</service>
<text>пострадавшим в Кемерове</text>
</charity>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>true</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
<node id="194.186.207.23">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<OKBRating>true</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>true</creditCardArrears>
<Spasibo>true</Spasibo>
<autoTransfers_7_10>true</autoTransfers_7_10>
<pciDss>true</pciDss>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost/>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showAllHistoryOperations>true</showAllHistoryOperations>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>true</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<enableContactManager>true</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>true</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
<node id="mobile.sberbank.ru">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<OKBRating>true</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>true</creditCardArrears>
<Spasibo>true</Spasibo>
<autoTransfers_7_10>true</autoTransfers_7_10>
<pciDss>true</pciDss>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost>pfl-psi.efstst.sigma.sbrf.ru:443</UFSHost>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>true</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<enableContactManager>true</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<charity>
<enabled>true</enabled>
<billing>4</billing>
<provider>3</provider>
<service>3</service>
<text>пострадавшим в Кемерове</text>
</charity>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>false</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<OKBRating>true</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>false</creditCardArrears>
<Spasibo>true</Spasibo>
<autoTransfers_7_10>true</autoTransfers_7_10>
<pciDss>true</pciDss>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost>ift.testefs.sberbank.ru:443</UFSHost>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showAllHistoryOperations>true</showAllHistoryOperations>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>false</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<enableContactManager>true</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>true</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<OKBRating>true</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>false</creditCardArrears>
<Spasibo>true</Spasibo>
<autoTransfers_7_10>true</autoTransfers_7_10>
<pciDss>true</pciDss>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost>ift.testefs.sberbank.ru:443</UFSHost>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showAllHistoryOperations>true</showAllHistoryOperations>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>false</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<enableContactManager>true</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>true</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<OKBRating>true</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>true</creditCardArrears>
<Spasibo>true</Spasibo>
<autoTransfers_7_10>true</autoTransfers_7_10>
<pciDss>true</pciDss>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost>ift.testefs.sberbank.ru:443</UFSHost>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showAllHistoryOperations>true</showAllHistoryOperations>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>false</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<enableContactManager>true</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>true</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<OKBRating>true</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>true</creditCardArrears>
<Spasibo>true</Spasibo>
<autoTransfers_7_10>true</autoTransfers_7_10>
<pciDss>true</pciDss>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost>ift.testefs.sberbank.ru:443</UFSHost>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showAllHistoryOperations>true</showAllHistoryOperations>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>false</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<enableContactManager>true</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>true</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
<node id="10.21.152.7">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<OKBRating>true</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>true</creditCardArrears>
<Spasibo>true</Spasibo>
<autoTransfers_7_10>true</autoTransfers_7_10>
<pciDss>true</pciDss>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost>sbt-oafs-498.sigma.sbrf.ru:443</UFSHost>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showAllHistoryOperations>true</showAllHistoryOperations>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>true</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<enableContactManager>true</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>true</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
<node id="sbt-oafs-703.sigma.sbrf.ru">
<coreQR>true</coreQR>
<smart_inbox>true</smart_inbox>
<accountclosing>true</accountclosing>
<arrests>true</arrests>
<SBTelecom>true</SBTelecom>
<CreditRating>false</CreditRating>
<OKBRating>true</OKBRating>
<deliveryCard>true</deliveryCard>
<creditCardArrears>true</creditCardArrears>
<Spasibo>true</Spasibo>
<autoTransfers_7_10>true</autoTransfers_7_10>
<pciDss>true</pciDss>
<creditCardAutorepayment>true</creditCardAutorepayment>
<governmentServices>true</governmentServices>
<pensionTransfer_actual>true</pensionTransfer_actual>
<pensionCertificate>true</pensionCertificate>
<criminalRecord>true</criminalRecord>
<UFSHost/>
<LoanDetailInfo>true</LoanDetailInfo>
<EarlyLoanRepaymentClaim>true</EarlyLoanRepaymentClaim>
<privacyPolicy>true</privacyPolicy>
<overseasTransfer>true</overseasTransfer>
<AutotransferUpdateStatus>true</AutotransferUpdateStatus>
<OmniChannelHistory>true</OmniChannelHistory>
<showUfsHistoryOperations>true</showUfsHistoryOperations>
<gibddSaveLicenseAndVRC>true</gibddSaveLicenseAndVRC>
<EribPenaltyDocumentsSavingAllowed>true</EribPenaltyDocumentsSavingAllowed>
<EribPenaltyDocumentsListEnabled>true</EribPenaltyDocumentsListEnabled>
<EribPenaltyLoadingAutoretry>true</EribPenaltyLoadingAutoretry>
<EribStatePaymentShortCutsEnabled>true</EribStatePaymentShortCutsEnabled>
<blockedCardsStatusWay4>true</blockedCardsStatusWay4>
<enableContactManager>true</enableContactManager>
<coursesOnMain>true</coursesOnMain>
<historyRouterEnabled>true</historyRouterEnabled>
<historyRefactoredList>true</historyRefactoredList>
<EribEBillingUtilitiesReceiptShowButtonEnabled>true</EribEBillingUtilitiesReceiptShowButtonEnabled>
<webAnalyticsEnabled>true</webAnalyticsEnabled>
<newSectionInvestEnable>true</newSectionInvestEnable>
<interTransfer>true</interTransfer>
<IsFromAddrBook>true</IsFromAddrBook>
</node>
</nodes>
</param>
<param name="ufsOperationDetailHistoryAlert" description="">
<type>strings</type>
<string>
Вы не можете посмотреть данную операцию через мобильное приложение. Для просмотра воспользуйтесь веб-версией Сбербанк Онлайн.
</string>
</param>
<param name="extendedPermission" description="">
<type>list</type>
<nodes>
<node id="ift-node1-mp.testonline.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>true</disabledPermissions>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="mobile.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
</node>
<node id="10.21.152.7">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="greenfield1.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="greenfield2.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="node0.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="node1.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="node2.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="node3.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
<node id="node4.online.sberbank.ru">
<extendedPermissionEnabled>true</extendedPermissionEnabled>
<disabledPermissions>false</disabledPermissions>
</node>
</nodes>
</param>
<param name="900Permissions" description="">
<type>list</type>
<pushAlertTimeInterval>10</pushAlertTimeInterval>
<efsMobileBank>true</efsMobileBank>
<nodes>
<node id="node0.online.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
<efsMobileBank>true</efsMobileBank>
</node>
<node id="node1.online.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
<efsMobileBank>true</efsMobileBank>
</node>
<node id="node2.online.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
<efsMobileBank>true</efsMobileBank>
</node>
<node id="node3.online.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
<efsMobileBank>true</efsMobileBank>
</node>
<node id="greenfield1.online.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
<efsMobileBank>true</efsMobileBank>
</node>
<node id="194.186.207.23">
<pushAlertEnabled>true</pushAlertEnabled>
<efsMobileBank>true</efsMobileBank>
</node>
<node id="mobile.sberbank.ru">
<pushAlertEnabled>true</pushAlertEnabled>
<efsMobileBank>true</efsMobileBank>
</node>
</nodes>
</param>
<param name="mirTokenizationBINs" description="Список бинов карт платежной системы МИР, доступных для токенизации">
<type>list</type>
<enabled>true</enabled>
<BINsCollection>
<BINs paymentSystem="MIR">
<BINrangeCollection>
<BINrange start="220220"/>
</BINrangeCollection>
</BINs>
</BINsCollection>
</param>
<param name="tokenizationBINs" description="">
<type>list</type>
<enabled>true</enabled>
<BINsCollection>
<BINs paymentSystem="MasterCard">
<BINrangeCollection>
<BINrange start="521439" end="521441"/>
<BINrange start="521447" end="521448"/>
<BINrange start="522169"/>
<BINrange start="522351"/>
<BINrange start="522385"/>
<BINrange start="526236"/>
<BINrange start="526253" end="526254"/>
<BINrange start="526260"/>
<BINrange start="527473"/>
<BINrange start="527476"/>
<BINrange start="531310"/>
<BINrange start="533205"/>
<BINrange start="533208"/>
<BINrange start="533669"/>
<BINrange start="553012" end="553016"/>
<BINrange start="553018" end="553023"/>
<BINrange start="553026" end="553027"/>
<BINrange start="553029"/>
<BINrange start="536961"/>
<BINrange start="545152"/>
<BINrange start="546901"/>
<BINrange start="546902" end="546913"/>
<BINrange start="546916" end="546918"/>
<BINrange start="546920"/>
<BINrange start="546922"/>
<BINrange start="546925" end="546933"/>
<BINrange start="546935"/>
<BINrange start="546937" end="546956"/>
<BINrange start="546959" end="546964"/>
<BINrange start="546966" end="546970"/>
<BINrange start="546972"/>
<BINrange start="546974" end="546977"/>
<BINrange start="546998" end="546999"/>
<BINrange start="547927"/>
<BINrange start="548401"/>
<BINrange start="548402" end="548403"/>
<BINrange start="548405" end="548407"/>
<BINrange start="548410" end="548413"/>
<BINrange start="548416"/>
<BINrange start="548420"/>
<BINrange start="548422"/>
<BINrange start="548425" end="548428"/>
<BINrange start="548430" end="548432"/>
<BINrange start="548435" end="548436"/>
<BINrange start="548438"/>
<BINrange start="548440"/>
<BINrange start="548442" end="548445"/>
<BINrange start="548447" end="548452"/>
<BINrange start="548454" end="548456"/>
<BINrange start="548459" end="548464"/>
<BINrange start="548466"/>
<BINrange start="548468" end="548469"/>
<BINrange start="548470"/>
<BINrange start="548472"/>
<BINrange start="548476" end="548477"/>
<BINrange start="548498" end="548499"/>
<BINrange start="557000"/>
</BINrangeCollection>
</BINs>
<BINs paymentSystem="VISA">
<BINrangeCollection>
<BINrange start="417398"/>
<BINrange start="427400"/>
<BINrange start="427402" end="427404"/>
<BINrange start="427406" end="427408"/>
<BINrange start="427411" end="427413"/>
<BINrange start="427416" end="427418"/>
<BINrange start="427420"/>
<BINrange start="427422"/>
<BINrange start="427425" end="427428"/>
<BINrange start="427430" end="427433"/>
<BINrange start="427436"/>
<BINrange start="427438" end="427442"/>
<BINrange start="427444" end="427446"/>
<BINrange start="427448" end="427456"/>
<BINrange start="427459" end="427463"/>
<BINrange start="427466" end="427470"/>
<BINrange start="427472"/>
<BINrange start="427475"/>
<BINrange start="427477"/>
<BINrange start="427499"/>
<BINrange start="427601" end="427613"/>
<BINrange start="427616" end="427618"/>
<BINrange start="427620"/>
<BINrange start="427622"/>
<BINrange start="427625" end="427633"/>
<BINrange start="427635" end="427646"/>
<BINrange start="427648" end="427656"/>
<BINrange start="427659" end="427664"/>
<BINrange start="427666" end="427670"/>
<BINrange start="427672"/>
<BINrange start="427674" end="427677"/>
<BINrange start="427680" end="427687"/>
<BINrange start="427689"/>
<BINrange start="427699"/>
<BINrange start="427901" end="427913"/>
<BINrange start="427916" end="427918"/>
<BINrange start="427920"/>
<BINrange start="427922"/>
<BINrange start="427925" end="427933"/>
<BINrange start="427935" end="427946"/>
<BINrange start="427948" end="427956"/>
<BINrange start="427959" end="427964"/>
<BINrange start="427966" end="427970"/>
<BINrange start="427972"/>
<BINrange start="427974" end="427975"/>
<BINrange start="427977"/>
<BINrange start="427999"/>
<BINrange start="481776"/>
<BINrange start="481779"/>
<BINrange start="481781"/>
<BINrange start="483983"/>
<BINrange start="485463"/>
</BINrangeCollection>
</BINs>
</BINsCollection>
</param>
<param name="mastercard_tokenisation" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="visa_tokenisation" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="mir_tokenization" description="">
<type>setting</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="SelfRegistrationCSAmApi7_9up" description="Включение mAPI на этапе саморегистрации в мобильном приложении">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="CardRegistrationApp" description="Включение регистрации устройства по номеру карты">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="LoginBirthdayRegistrationApp" description="Включение регистрации по логину и дате рождения">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="CardPushEnabled" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="beta" description="Рубильник бета версии">
<type>setting</type>
<enabled>true</enabled>
<string>
Уважаемые пользователи бета-версии! Текущая бета-версия находится на доработке, следите за обновлениями в Google Play. Спасибо за Ваше участие и отзывы!
</string>
</param>
<param name="aim_withDeposit" description="Открытие цели с выбором типа вклада">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="androidPay_tokenization" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="samsungPay_tokenization" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="nfcTokensManagement" description="Управление жизненным циклом токена">
<type>list</type>
<enabled>true</enabled>
<nfcTokensManagementVisa>true</nfcTokensManagementVisa>
<nfcTokensManagementMC>true</nfcTokensManagementMC>
</param>
<param name="e_invoicing" description="Инвойсинг">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="without_confirmation_payment" description="Безакцептное списание">
<type>service</type>
<enabled>true</enabled>
<value>2000</value>
<link>
http://www.sberbank.ru/common/img/uploaded/files/pdf/Manual_Android.pdf
</link>
</param>
<param name="signOnParams" description="Парамтеры стрима SignOn">
<type>list</type>
<androidPayClientDataTransferOffer>
http://www.sberbank.ru/common/img/uploaded/files/pdf/Manual_Android.pdf
</androidPayClientDataTransferOffer>
<offerNonAccept>
http://www.sberbank.ru/common/img/uploaded/files/pdf/usloviya_perevoda.pdf
</offerNonAccept>
<androidPayAutocompleteChecked>false</androidPayAutocompleteChecked>
<tokenInfoReqOnNewRegistration>true</tokenInfoReqOnNewRegistration>
<tokenInfoReqOnNewRegistrationMC>true</tokenInfoReqOnNewRegistrationMC>
<tokenInfoReqOnNewRegistrationVisa>true</tokenInfoReqOnNewRegistrationVisa>
<tokenInfoReqOnAddCardMC>true</tokenInfoReqOnAddCardMC>
<tokenInfoReqOnAddCardVisa>true</tokenInfoReqOnAddCardVisa>
<tokenInfoReqOnListChangeMC>true</tokenInfoReqOnListChangeMC>
<tokenInfoReqOnListChangeVisa>true</tokenInfoReqOnListChangeVisa>
<merchantDataManagementServiceName>Управление Sberbank ID</merchantDataManagementServiceName>
<nodes>
<node id="node0.online.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<androidPayClientDataAutoComplete>true</androidPayClientDataAutoComplete>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="node1.online.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<androidPayClientDataAutoComplete>true</androidPayClientDataAutoComplete>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="node2.online.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<androidPayClientDataAutoComplete>true</androidPayClientDataAutoComplete>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="node3.online.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<androidPayClientDataAutoComplete>true</androidPayClientDataAutoComplete>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="greenfield1.online.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<androidPayClientDataAutoComplete>true</androidPayClientDataAutoComplete>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="194.186.207.23">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<androidPayClientDataAutoComplete>true</androidPayClientDataAutoComplete>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="mobile.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<androidPayClientDataAutoComplete>true</androidPayClientDataAutoComplete>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<androidPayClientDataAutoComplete>true</androidPayClientDataAutoComplete>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<androidPayClientDataAutoComplete>true</androidPayClientDataAutoComplete>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<androidPayClientDataAutoComplete>true</androidPayClientDataAutoComplete>
<merchantDataManagement>true</merchantDataManagement>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<qrPayments>true</qrPayments>
<qrP2P>true</qrP2P>
<qrMerchantBinding>true</qrMerchantBinding>
<androidPayClientDataAutoComplete>true</androidPayClientDataAutoComplete>
<merchantDataManagement>true</merchantDataManagement>
</node>
</nodes>
</param>
<param name="EasyLogin" description="Включение новых правил создания логина">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="MessengerPermissions" description="">
<type>list</type>
<authMessengerLogin>true</authMessengerLogin>
<MessengerFirework>true</MessengerFirework>
<nodes>
<node id="node0.online.sberbank.ru">
<MessengerLogin>true</MessengerLogin>
<MessengerP2P>true</MessengerP2P>
<P2PNonUserMessenger>true</P2PNonUserMessenger>
<p2pAuth>true</p2pAuth>
<timeToRefreshUnread>20</timeToRefreshUnread>
<MessengerRemoveConversation>true</MessengerRemoveConversation>
<MessengerEmoji>true</MessengerEmoji>
<MessengerPushSettings>true</MessengerPushSettings>
<MessengerSuggestions>true</MessengerSuggestions>
<MessengerOnlineSuggestions>true</MessengerOnlineSuggestions>
<MessengerStickers>true</MessengerStickers>
<MessengerPostcard>true</MessengerPostcard>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardView>true</MessengerPostcardView>
<MessengerPostcardEditSum>true</MessengerPostcardEditSum>
<Markdown>true</Markdown>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPinning>true</MessengerPinning>
</node>
<node id="node1.online.sberbank.ru">
<MessengerLogin>true</MessengerLogin>
<MessengerP2P>true</MessengerP2P>
<P2PNonUserMessenger>true</P2PNonUserMessenger>
<p2pAuth>true</p2pAuth>
<timeToRefreshUnread>20</timeToRefreshUnread>
<MessengerRemoveConversation>true</MessengerRemoveConversation>
<MessengerEmoji>true</MessengerEmoji>
<MessengerPushSettings>true</MessengerPushSettings>
<MessengerSuggestions>true</MessengerSuggestions>
<MessengerOnlineSuggestions>true</MessengerOnlineSuggestions>
<MessengerStickers>true</MessengerStickers>
<MessengerPostcard>true</MessengerPostcard>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardView>true</MessengerPostcardView>
<MessengerPostcardEditSum>true</MessengerPostcardEditSum>
<Markdown>true</Markdown>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPinning>true</MessengerPinning>
</node>
<node id="node2.online.sberbank.ru">
<MessengerLogin>true</MessengerLogin>
<MessengerP2P>true</MessengerP2P>
<P2PNonUserMessenger>true</P2PNonUserMessenger>
<p2pAuth>true</p2pAuth>
<timeToRefreshUnread>20</timeToRefreshUnread>
<MessengerRemoveConversation>true</MessengerRemoveConversation>
<MessengerEmoji>true</MessengerEmoji>
<MessengerPushSettings>true</MessengerPushSettings>
<MessengerSuggestions>true</MessengerSuggestions>
<MessengerOnlineSuggestions>true</MessengerOnlineSuggestions>
<MessengerStickers>true</MessengerStickers>
<MessengerPostcard>true</MessengerPostcard>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardView>true</MessengerPostcardView>
<MessengerPostcardEditSum>true</MessengerPostcardEditSum>
<Markdown>true</Markdown>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPinning>true</MessengerPinning>
</node>
<node id="node3.online.sberbank.ru">
<MessengerLogin>true</MessengerLogin>
<MessengerP2P>true</MessengerP2P>
<P2PNonUserMessenger>true</P2PNonUserMessenger>
<p2pAuth>true</p2pAuth>
<timeToRefreshUnread>20</timeToRefreshUnread>
<MessengerRemoveConversation>true</MessengerRemoveConversation>
<MessengerEmoji>true</MessengerEmoji>
<MessengerPushSettings>true</MessengerPushSettings>
<MessengerSuggestions>true</MessengerSuggestions>
<MessengerOnlineSuggestions>true</MessengerOnlineSuggestions>
<MessengerStickers>true</MessengerStickers>
<MessengerPostcard>true</MessengerPostcard>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardView>true</MessengerPostcardView>
<MessengerPostcardEditSum>true</MessengerPostcardEditSum>
<Markdown>true</Markdown>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPinning>true</MessengerPinning>
</node>
<node id="greenfield1.online.sberbank.ru">
<MessengerLogin>true</MessengerLogin>
<MessengerP2P>true</MessengerP2P>
<P2PNonUserMessenger>true</P2PNonUserMessenger>
<p2pAuth>true</p2pAuth>
<timeToRefreshUnread>20</timeToRefreshUnread>
<MessengerRemoveConversation>true</MessengerRemoveConversation>
<MessengerEmoji>true</MessengerEmoji>
<MessengerPushSettings>true</MessengerPushSettings>
<MessengerSuggestions>true</MessengerSuggestions>
<MessengerOnlineSuggestions>true</MessengerOnlineSuggestions>
<MessengerStickers>true</MessengerStickers>
<MessengerPostcard>true</MessengerPostcard>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardView>true</MessengerPostcardView>
<MessengerPostcardEditSum>true</MessengerPostcardEditSum>
<Markdown>true</Markdown>
<MessengerPinning>true</MessengerPinning>
</node>
<node id="194.186.207.23">
<MessengerLogin>true</MessengerLogin>
<MessengerP2P>true</MessengerP2P>
<P2PNonUserMessenger>true</P2PNonUserMessenger>
<p2pAuth>true</p2pAuth>
<timeToRefreshUnread>20</timeToRefreshUnread>
<MessengerRemoveConversation>true</MessengerRemoveConversation>
<MessengerEmoji>true</MessengerEmoji>
<MessengerPushSettings>true</MessengerPushSettings>
<MessengerSuggestions>true</MessengerSuggestions>
<MessengerOnlineSuggestions>true</MessengerOnlineSuggestions>
<MessengerStickers>true</MessengerStickers>
<MessengerPostcard>true</MessengerPostcard>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardView>true</MessengerPostcardView>
<MessengerPostcardEditSum>true</MessengerPostcardEditSum>
<Markdown>true</Markdown>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPinning>true</MessengerPinning>
</node>
<node id="mobile.sberbank.ru">
<MessengerLogin>true</MessengerLogin>
<MessengerP2P>true</MessengerP2P>
<P2PNonUserMessenger>true</P2PNonUserMessenger>
<p2pAuth>true</p2pAuth>
<timeToRefreshUnread>20</timeToRefreshUnread>
<MessengerRemoveConversation>true</MessengerRemoveConversation>
<MessengerEmoji>true</MessengerEmoji>
<MessengerPushSettings>true</MessengerPushSettings>
<MessengerSuggestions>true</MessengerSuggestions>
<MessengerOnlineSuggestions>true</MessengerOnlineSuggestions>
<MessengerStickers>true</MessengerStickers>
<MessengerPostcard>true</MessengerPostcard>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardView>true</MessengerPostcardView>
<MessengerPostcardEditSum>true</MessengerPostcardEditSum>
<Markdown>true</Markdown>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPinning>true</MessengerPinning>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<MessengerLogin>true</MessengerLogin>
<MessengerP2P>true</MessengerP2P>
<P2PNonUserMessenger>true</P2PNonUserMessenger>
<p2pAuth>true</p2pAuth>
<timeToRefreshUnread>20</timeToRefreshUnread>
<MessengerRemoveConversation>true</MessengerRemoveConversation>
<MessengerEmoji>true</MessengerEmoji>
<MessengerPushSettings>true</MessengerPushSettings>
<MessengerSuggestions>true</MessengerSuggestions>
<MessengerOnlineSuggestions>true</MessengerOnlineSuggestions>
<MessengerStickers>true</MessengerStickers>
<MessengerPostcard>true</MessengerPostcard>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardView>true</MessengerPostcardView>
<MessengerPostcardEditSum>true</MessengerPostcardEditSum>
<Markdown>true</Markdown>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPinning>true</MessengerPinning>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<MessengerLogin>true</MessengerLogin>
<MessengerP2P>true</MessengerP2P>
<P2PNonUserMessenger>true</P2PNonUserMessenger>
<p2pAuth>true</p2pAuth>
<timeToRefreshUnread>20</timeToRefreshUnread>
<MessengerRemoveConversation>true</MessengerRemoveConversation>
<MessengerEmoji>true</MessengerEmoji>
<MessengerPushSettings>true</MessengerPushSettings>
<MessengerSuggestions>true</MessengerSuggestions>
<MessengerOnlineSuggestions>true</MessengerOnlineSuggestions>
<MessengerStickers>true</MessengerStickers>
<MessengerPostcard>true</MessengerPostcard>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardView>true</MessengerPostcardView>
<MessengerPostcardEditSum>true</MessengerPostcardEditSum>
<Markdown>true</Markdown>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPinning>true</MessengerPinning>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<MessengerLogin>true</MessengerLogin>
<MessengerP2P>true</MessengerP2P>
<P2PNonUserMessenger>true</P2PNonUserMessenger>
<p2pAuth>true</p2pAuth>
<timeToRefreshUnread>20</timeToRefreshUnread>
<MessengerRemoveConversation>true</MessengerRemoveConversation>
<MessengerEmoji>true</MessengerEmoji>
<MessengerPushSettings>true</MessengerPushSettings>
<MessengerSuggestions>true</MessengerSuggestions>
<MessengerOnlineSuggestions>true</MessengerOnlineSuggestions>
<MessengerStickers>true</MessengerStickers>
<MessengerPostcard>true</MessengerPostcard>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardView>true</MessengerPostcardView>
<MessengerPostcardEditSum>true</MessengerPostcardEditSum>
<Markdown>true</Markdown>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPinning>true</MessengerPinning>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<MessengerLogin>true</MessengerLogin>
<MessengerP2P>true</MessengerP2P>
<P2PNonUserMessenger>true</P2PNonUserMessenger>
<p2pAuth>true</p2pAuth>
<timeToRefreshUnread>20</timeToRefreshUnread>
<MessengerRemoveConversation>true</MessengerRemoveConversation>
<MessengerEmoji>true</MessengerEmoji>
<MessengerPushSettings>true</MessengerPushSettings>
<MessengerSuggestions>true</MessengerSuggestions>
<MessengerOnlineSuggestions>true</MessengerOnlineSuggestions>
<MessengerStickers>true</MessengerStickers>
<MessengerPostcard>true</MessengerPostcard>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardView>true</MessengerPostcardView>
<MessengerPostcardEditSum>true</MessengerPostcardEditSum>
<Markdown>true</Markdown>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPinning>true</MessengerPinning>
</node>
<node id="mobile.sberbank.ru:7771">
<MessengerLogin>true</MessengerLogin>
<MessengerP2P>true</MessengerP2P>
<P2PNonUserMessenger>true</P2PNonUserMessenger>
<p2pAuth>true</p2pAuth>
<timeToRefreshUnread>20</timeToRefreshUnread>
<MessengerRemoveConversation>true</MessengerRemoveConversation>
<MessengerEmoji>true</MessengerEmoji>
<MessengerPushSettings>true</MessengerPushSettings>
<MessengerSuggestions>true</MessengerSuggestions>
<MessengerOnlineSuggestions>true</MessengerOnlineSuggestions>
<MessengerStickers>true</MessengerStickers>
<MessengerPostcard>true</MessengerPostcard>
<MessengerPostcardForNonClient>true</MessengerPostcardForNonClient>
<MessengerPostcardView>true</MessengerPostcardView>
<MessengerPostcardEditSum>true</MessengerPostcardEditSum>
<Markdown>true</Markdown>
<MessengerDocDoc>true</MessengerDocDoc>
<MessengerOpenDialogWithDeepLink>true</MessengerOpenDialogWithDeepLink>
<MessengerPinning>true</MessengerPinning>
</node>
</nodes>
</param>
<param name="aim_withCurrency" description="Открытие валютных целей">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="map" description="Рубильник для яндекс карт">
<type>list</type>
<enabled>true</enabled>
<features>
<feature id="ATMs" enabled="true"/>
<feature id="partners" enabled="true"/>
<feature id="creditCard" enabled="true"/>
<feature id="oms" enabled="true"/>
</features>
</param>
<param name="ExternalLogin" description="Включение аутентификации через СБОЛ на внешних ресурсах">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="SelectScope" description="Включение выбора scope для аутентификации через СБОЛ на внешних ресурсах">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="SberIDNewPinCode" description="Включение выделенного окна аутентификации SberbankID">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="WelfareProductsMainScreenV2" description="Продукты благосостояния на главном экране">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="WelfareProductsDetailsV2" description="Карточки продуктов благосостояния (детализация продукта)">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="WelfareTutorialV2" description="Туториал на фичу">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="WelfareProductsMainScreenV3" description="Продукты благосостояния на главном экране">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="WelfareProductsDetailsV3" description="Карточки продуктов благосостояния (детализация продукта)">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="WelfareTutorialV3" description="Туториал на фичу">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="WelfareLegacyContracts" description="Включение функционала первой версии сервиса ContractList">
<type>setting</type>
<enabled>false</enabled>
</param>
<param name="EfsInsuranceContractsFeatureToggle" description="Отображение контрактов по страховым продуктам">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="UfsInsuranceOther" description="Отображение раздела Страхование в Прочее после релиза 8.3 включительно">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="EfsInsuranceSupportModuleToggle" description="Рубильник для модуля ППО страховых продуктов">
<type>list</type>
<enabled>false</enabled>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="194.186.207.23">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="mobile.sberbank.ru">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="node0.online.sberbank.ru">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="node1.online.sberbank.ru">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="node2.online.sberbank.ru">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="node3.online.sberbank.ru">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="10.21.152.7">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
<node id="msv-node2.testonline.sberbank.ru">
<InsuranceSupportApplicationFeatureEnabled>false</InsuranceSupportApplicationFeatureEnabled>
<InsuranceSupportDuplicateFeatureEnabled>false</InsuranceSupportDuplicateFeatureEnabled>
<InsuranceSupportCancellationFeatureEnabled>false</InsuranceSupportCancellationFeatureEnabled>
<InsuranceSupportBeneficiaryFeatureEnabled>false</InsuranceSupportBeneficiaryFeatureEnabled>
</node>
</nodes>
</param>
<param name="welfareProducts" description="Продукты благосостояния">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="194.186.207.23">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="mobile.sberbank.ru">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="node0.online.sberbank.ru">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="node1.online.sberbank.ru">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="node2.online.sberbank.ru">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="node3.online.sberbank.ru">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="ift-node5-mp.testonline.sberbank.ru">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="10.21.152.7">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
<node id="msv-node2.testonline.sberbank.ru">
<InsuranceEnabled>true</InsuranceEnabled>
<PensionEnabled>false</PensionEnabled>
<PensionEnabled_2.0>true</PensionEnabled_2.0>
<InvestmentsEnabled>true</InvestmentsEnabled>
<isShowInFinance>true</isShowInFinance>
<isShowInFinancev2>true</isShowInFinancev2>
<actionInvestmentsBuy>true</actionInvestmentsBuy>
<actionPIF>true</actionPIF>
<actionIPP>true</actionIPP>
</node>
</nodes>
</param>
<param name="UfsInsuranceHistory" description="История операций по Страховым продуктам">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="UfsPensionPersonalPlanHistory" description="История операций по продукту Миллион на пенсию">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="UfsInvestmentsFundHistory" description="История операций по продукту ПИФ">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="brokerage" description="Брокерское обслуживание">
<enabled>true</enabled>
<replenishAccountEnabled>true</replenishAccountEnabled>
<replenishAccountInMarginCallEnabled>true</replenishAccountInMarginCallEnabled>
<replenishAccountSearchString>Пополнение Брокерского Счёта</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S133717540667A133717540630)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S133717540667A133717540638)</replenishAccountMarketFieldCode>
<createDocApplicationEnabled>true</createDocApplicationEnabled>
<brokerageHelpPhoneNumber>900</brokerageHelpPhoneNumber>
<brokerageProductsAvailableInFinance>true</brokerageProductsAvailableInFinance>
<nodes>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<replenishAccountSearchString>Пополнение Брокерского Счёта</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S133717540667A133717540630)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S133717540667A133717540638)</replenishAccountMarketFieldCode>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<replenishAccountSearchString>Пополнение брокерского счета</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S85396525721A85396525552)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S85396525721A85396525571)</replenishAccountMarketFieldCode>
</node>
<node id="10.21.152.7">
<enabled>true</enabled>
<replenishAccountSearchString>Пополнение Брокерского Счёта</replenishAccountSearchString>
<replenishAccountAgreementFieldCode>field(S133717540667A133717540630)</replenishAccountAgreementFieldCode>
<replenishAccountMarketFieldCode>field(S133717540667A133717540638)</replenishAccountMarketFieldCode>
</node>
</nodes>
<markets>
<market id="0">
<enabled>true</enabled>
</market>
<market id="1">
<enabled>true</enabled>
</market>
<market id="2">
<enabled>false</enabled>
</market>
</markets>
</param>
<param name="offers_config" description="Предложения продуктов на витринах продаж">
<type>list</type>
<enabled>true</enabled>
<places>
<mainScreenSections>
<credit>
<enabled>true</enabled>
<limit>2147483647</limit>
<requestAfterClick>true</requestAfterClick>
</credit>
</mainScreenSections>
<mainScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
</mainScreen>
<successScreen>
<enabled>true</enabled>
<limit>2147483647</limit>
</successScreen>
</places>
<nodes>
<node id="node0.online.sberbank.ru">
<abTestingSuccessScreenEnabled>false</abTestingSuccessScreenEnabled>
<defaultDesignSuccessScreen>b</defaultDesignSuccessScreen>
<storiesMainScreenMVP>
<enabled>true</enabled>
<limit>2147483647</limit>
</storiesMainScreenMVP>
<storiesMainScreenClosed>true</storiesMainScreenClosed>
<storiesMainScreenOpened>false</storiesMainScreenOpened>
<places>
<mainScreenSections>
<credit>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</credit>
</mainScreenSections>
<storiesMainScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</storiesMainScreen>
<successScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</successScreen>
</places>
</node>
<node id="node1.online.sberbank.ru">
<abTestingSuccessScreenEnabled>false</abTestingSuccessScreenEnabled>
<defaultDesignSuccessScreen>b</defaultDesignSuccessScreen>
<storiesMainScreenMVP>
<enabled>true</enabled>
<limit>2147483647</limit>
</storiesMainScreenMVP>
<storiesMainScreenClosed>true</storiesMainScreenClosed>
<storiesMainScreenOpened>false</storiesMainScreenOpened>
<places>
<mainScreenSections>
<credit>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</credit>
</mainScreenSections>
<storiesMainScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</storiesMainScreen>
<successScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</successScreen>
</places>
</node>
<node id="node2.online.sberbank.ru">
<abTestingSuccessScreenEnabled>false</abTestingSuccessScreenEnabled>
<defaultDesignSuccessScreen>b</defaultDesignSuccessScreen>
<storiesMainScreenMVP>
<enabled>true</enabled>
<limit>2147483647</limit>
</storiesMainScreenMVP>
<storiesMainScreenClosed>false</storiesMainScreenClosed>
<storiesMainScreenOpened>true</storiesMainScreenOpened>
<places>
<mainScreenSections>
<credit>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</credit>
</mainScreenSections>
<storiesMainScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</storiesMainScreen>
<successScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</successScreen>
</places>
</node>
<node id="node3.online.sberbank.ru">
<abTestingSuccessScreenEnabled>false</abTestingSuccessScreenEnabled>
<defaultDesignSuccessScreen>b</defaultDesignSuccessScreen>
<storiesMainScreenMVP>
<enabled>true</enabled>
<limit>2147483647</limit>
</storiesMainScreenMVP>
<storiesMainScreenClosed>true</storiesMainScreenClosed>
<storiesMainScreenOpened>false</storiesMainScreenOpened>
<places>
<mainScreenSections>
<credit>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</credit>
</mainScreenSections>
<storiesMainScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</storiesMainScreen>
<successScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</successScreen>
</places>
</node>
<node id="greenfield1.online.sberbank.ru">
<abTestingSuccessScreenEnabled>false</abTestingSuccessScreenEnabled>
<defaultDesignSuccessScreen>b</defaultDesignSuccessScreen>
<storiesMainScreenMVP>
<enabled>true</enabled>
<limit>2147483647</limit>
</storiesMainScreenMVP>
<storiesMainScreenClosed>true</storiesMainScreenClosed>
<storiesMainScreenOpened>false</storiesMainScreenOpened>
<places>
<mainScreenSections>
<credit>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</credit>
</mainScreenSections>
<storiesMainScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</storiesMainScreen>
<successScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</successScreen>
</places>
</node>
<node id="mobile.sberbank.ru">
<abTestingSuccessScreenEnabled>false</abTestingSuccessScreenEnabled>
<defaultDesignSuccessScreen>b</defaultDesignSuccessScreen>
<storiesMainScreenMVP>
<enabled>true</enabled>
<limit>2147483647</limit>
</storiesMainScreenMVP>
<storiesMainScreenClosed>true</storiesMainScreenClosed>
<storiesMainScreenOpened>false</storiesMainScreenOpened>
<places>
<mainScreenSections>
<credit>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</credit>
</mainScreenSections>
<storiesMainScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</storiesMainScreen>
<successScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</successScreen>
</places>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<abTestingSuccessScreenEnabled>false</abTestingSuccessScreenEnabled>
<defaultDesignSuccessScreen>b</defaultDesignSuccessScreen>
<storiesMainScreenMVP>
<enabled>true</enabled>
<limit>2147483647</limit>
</storiesMainScreenMVP>
<storiesMainScreenClosed>true</storiesMainScreenClosed>
<storiesMainScreenOpened>false</storiesMainScreenOpened>
<places>
<mainScreenSections>
<credit>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</credit>
</mainScreenSections>
<storiesMainScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</storiesMainScreen>
<successScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</successScreen>
</places>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<abTestingSuccessScreenEnabled>false</abTestingSuccessScreenEnabled>
<defaultDesignSuccessScreen>b</defaultDesignSuccessScreen>
<storiesMainScreenMVP>
<enabled>true</enabled>
<limit>2147483647</limit>
</storiesMainScreenMVP>
<storiesMainScreenClosed>false</storiesMainScreenClosed>
<storiesMainScreenOpened>true</storiesMainScreenOpened>
<places>
<mainScreenSections>
<credit>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</credit>
</mainScreenSections>
<storiesMainScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</storiesMainScreen>
<successScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</successScreen>
</places>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<abTestingSuccessScreenEnabled>false</abTestingSuccessScreenEnabled>
<defaultDesignSuccessScreen>b</defaultDesignSuccessScreen>
<storiesMainScreenMVP>
<enabled>true</enabled>
<limit>2147483647</limit>
</storiesMainScreenMVP>
<storiesMainScreenClosed>true</storiesMainScreenClosed>
<storiesMainScreenOpened>false</storiesMainScreenOpened>
<places>
<mainScreenSections>
<credit>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</credit>
</mainScreenSections>
<storiesMainScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</storiesMainScreen>
<successScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</successScreen>
</places>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<abTestingSuccessScreenEnabled>false</abTestingSuccessScreenEnabled>
<defaultDesignSuccessScreen>b</defaultDesignSuccessScreen>
<storiesMainScreenMVP>
<enabled>true</enabled>
<limit>2147483647</limit>
</storiesMainScreenMVP>
<storiesMainScreenClosed>false</storiesMainScreenClosed>
<storiesMainScreenOpened>true</storiesMainScreenOpened>
<places>
<mainScreenSections>
<credit>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</credit>
</mainScreenSections>
<storiesMainScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</storiesMainScreen>
<successScreen>
<contentSourceTipsBroker>true</contentSourceTipsBroker>
</successScreen>
</places>
</node>
</nodes>
</param>
<param name="TxPushSuggestion" description=" ">
<type>setting</type>
<enabled>true</enabled>
<periodInDays>1</periodInDays>
<number>3</number>
<delayInHours>12</delayInHours>
</param>
<param name="MobileBankSettings" description="Настройки для подключения МБ в МП">
<type>list</type>
<nodes>
<node id="mobile.sberbank.ru">
<targetTapToActivationMobileBank>true</targetTapToActivationMobileBank>
<mobileBankFromSettings>true</mobileBankFromSettings>
<turnOffFullTariffEnabled>true</turnOffFullTariffEnabled>
<efsMobileBank82>true</efsMobileBank82>
<showNotificationWS>true</showNotificationWS>
<turnOffFullTariffEnabled83>true</turnOffFullTariffEnabled83>
<doNotShowMobileBankStatusAtCardSettings>false</doNotShowMobileBankStatusAtCardSettings>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<targetTapToActivationMobileBank>true</targetTapToActivationMobileBank>
<mobileBankFromSettings>true</mobileBankFromSettings>
<turnOffFullTariffEnabled>true</turnOffFullTariffEnabled>
<efsMobileBank82>true</efsMobileBank82>
<showNotificationWS>true</showNotificationWS>
<turnOffFullTariffEnabled83>true</turnOffFullTariffEnabled83>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<targetTapToActivationMobileBank>true</targetTapToActivationMobileBank>
<mobileBankFromSettings>true</mobileBankFromSettings>
<turnOffFullTariffEnabled>true</turnOffFullTariffEnabled>
<efsMobileBank82>true</efsMobileBank82>
<showNotificationWS>true</showNotificationWS>
<turnOffFullTariffEnabled83>true</turnOffFullTariffEnabled83>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<targetTapToActivationMobileBank>true</targetTapToActivationMobileBank>
<mobileBankFromSettings>true</mobileBankFromSettings>
<turnOffFullTariffEnabled>true</turnOffFullTariffEnabled>
<efsMobileBank82>true</efsMobileBank82>
<showNotificationWS>true</showNotificationWS>
<turnOffFullTariffEnabled83>true</turnOffFullTariffEnabled83>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<targetTapToActivationMobileBank>true</targetTapToActivationMobileBank>
<mobileBankFromSettings>true</mobileBankFromSettings>
<turnOffFullTariffEnabled>true</turnOffFullTariffEnabled>
<efsMobileBank82>true</efsMobileBank82>
<showNotificationWS>true</showNotificationWS>
<turnOffFullTariffEnabled83>true</turnOffFullTariffEnabled83>
</node>
<node id="node4.online.sberbank.ru">
<targetTapToActivationMobileBank>true</targetTapToActivationMobileBank>
<mobileBankFromSettings>true</mobileBankFromSettings>
<turnOffFullTariffEnabled>true</turnOffFullTariffEnabled>
<efsMobileBank82>true</efsMobileBank82>
<showNotificationWS>true</showNotificationWS>
<turnOffFullTariffEnabled83>true</turnOffFullTariffEnabled83>
</node>
</nodes>
</param>
<param name="PushPermissions" description="Консолидированные включатели для функционала команды Push">
<type>list</type>
<nodes>
<node id="mobile.sberbank.ru">
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<alternativePushSettingTexts>true</alternativePushSettingTexts>
<pushPreEnrichment>false</pushPreEnrichment>
<updateTokenForegroundService>true</updateTokenForegroundService>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<alternativePushSettingTexts>true</alternativePushSettingTexts>
<pushPreEnrichment>false</pushPreEnrichment>
<updateTokenForegroundService>true</updateTokenForegroundService>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<alternativePushSettingTexts>true</alternativePushSettingTexts>
<pushPreEnrichment>false</pushPreEnrichment>
<updateTokenForegroundService>true</updateTokenForegroundService>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<alternativePushSettingTexts>true</alternativePushSettingTexts>
<pushPreEnrichment>false</pushPreEnrichment>
<updateTokenForegroundService>true</updateTokenForegroundService>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<alternativePushSettingTexts>true</alternativePushSettingTexts>
<pushPreEnrichment>false</pushPreEnrichment>
<updateTokenForegroundService>true</updateTokenForegroundService>
</node>
<node id="node4.online.sberbank.ru">
<autoTurnOffOperationPush>true</autoTurnOffOperationPush>
<alternativePushSettingTexts>true</alternativePushSettingTexts>
<pushPreEnrichment>false</pushPreEnrichment>
<updateTokenForegroundService>true</updateTokenForegroundService>
</node>
</nodes>
</param>
<param name="SberChat" description="Диалог с контактом 900">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<dialog900>false</dialog900>
</node>
<node id="node1.online.sberbank.ru">
<dialog900>false</dialog900>
</node>
<node id="node2.online.sberbank.ru">
<dialog900>false</dialog900>
</node>
<node id="node3.online.sberbank.ru">
<dialog900>false</dialog900>
</node>
<node id="greenfield1.online.sberbank.ru">
<dialog900>true</dialog900>
</node>
<node id="mobile.sberbank.ru">
<dialog900>true</dialog900>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<dialog900>true</dialog900>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<dialog900>true</dialog900>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<dialog900>true</dialog900>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<dialog900>true</dialog900>
</node>
</nodes>
</param>
<param name="SberChatTutorial" description="Туториал для диалога со Сбербанком">
<type>list</type>
<enabled>true</enabled>
<showTutorial>true</showTutorial>
</param>
<param name="digitalCreditMainSwitch" description="Рубильник всего кредитного функционала">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="digitalCreditCustomers" description="Список серверов, за которыми закреплены клиенты, которым доступен конкретный функционал">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="ift-node1.testonline.sberbank.ru">
<loanRequest>
<version id="8.2">
<enabled>true</enabled>
</version>
<version id="8.3">
<enabled>true</enabled>
</version>
<version id="8.4">
<enabled>true</enabled>
</version>
<version id="1.1">
<enabled>true</enabled>
</version>
</loanRequest>
<shortLoanRequest>true</shortLoanRequest>
<loanRequestWithIssue>true</loanRequestWithIssue>
<loanRequest_8.0>true</loanRequest_8.0>
<deepLinkToConsumerLoan>true</deepLinkToConsumerLoan>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<loanRequest>
<version id="8.2">
<enabled>true</enabled>
</version>
<version id="8.3">
<enabled>true</enabled>
</version>
<version id="8.4">
<enabled>true</enabled>
</version>
<version id="1.1">
<enabled>true</enabled>
</version>
</loanRequest>
<shortLoanRequest>true</shortLoanRequest>
<loanRequestWithIssue>true</loanRequestWithIssue>
<loanRequest_8.0>true</loanRequest_8.0>
<deepLinkToConsumerLoan>true</deepLinkToConsumerLoan>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<loanRequest>
<version id="8.2">
<enabled>true</enabled>
</version>
<version id="8.3">
<enabled>true</enabled>
</version>
<version id="8.4">
<enabled>true</enabled>
</version>
<version id="1.1">
<enabled>true</enabled>
</version>
</loanRequest>
<shortLoanRequest>true</shortLoanRequest>
<loanRequestWithIssue>true</loanRequestWithIssue>
<loanRequest_8.0>true</loanRequest_8.0>
<deepLinkToConsumerLoan>true</deepLinkToConsumerLoan>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<loanRequest>
<version id="8.2">
<enabled>true</enabled>
</version>
<version id="8.3">
<enabled>true</enabled>
</version>
<version id="8.4">
<enabled>true</enabled>
</version>
<version id="1.1">
<enabled>true</enabled>
</version>
</loanRequest>
<shortLoanRequest>true</shortLoanRequest>
<loanRequestWithIssue>true</loanRequestWithIssue>
<loanRequest_8.0>true</loanRequest_8.0>
<deepLinkToConsumerLoan>true</deepLinkToConsumerLoan>
</node>
<node id="mobile.sberbank.ru">
<loanRequest>
<version id="8.2">
<enabled>true</enabled>
</version>
<version id="8.3">
<enabled>true</enabled>
</version>
<version id="8.4">
<enabled>true</enabled>
</version>
<version id="1.1">
<enabled>true</enabled>
</version>
</loanRequest>
<shortLoanRequest>true</shortLoanRequest>
<loanRequestWithIssue>true</loanRequestWithIssue>
<loanRequest_8.0>true</loanRequest_8.0>
<deepLinkToConsumerLoan>true</deepLinkToConsumerLoan>
</node>
<node id="greenfield1.online.sberbank.ru">
<loanRequest>
<version id="8.2">
<enabled>true</enabled>
</version>
<version id="8.3">
<enabled>true</enabled>
</version>
<version id="8.4">
<enabled>true</enabled>
</version>
<version id="1.1">
<enabled>true</enabled>
</version>
</loanRequest>
<shortLoanRequest>true</shortLoanRequest>
<loanRequestWithIssue>true</loanRequestWithIssue>
<loanRequest_8.0>true</loanRequest_8.0>
<deepLinkToConsumerLoan>true</deepLinkToConsumerLoan>
</node>
<node id="node0.online.sberbank.ru">
<loanRequest>
<version id="8.2">
<enabled>true</enabled>
</version>
<version id="8.3">
<enabled>true</enabled>
</version>
<version id="8.4">
<enabled>true</enabled>
</version>
<version id="1.1">
<enabled>true</enabled>
</version>
</loanRequest>
<shortLoanRequest>true</shortLoanRequest>
<loanRequestWithIssue>true</loanRequestWithIssue>
<loanRequest_8.0>true</loanRequest_8.0>
<deepLinkToConsumerLoan>true</deepLinkToConsumerLoan>
</node>
<node id="node1.online.sberbank.ru">
<loanRequest>
<version id="8.2">
<enabled>true</enabled>
</version>
<version id="8.3">
<enabled>true</enabled>
</version>
<version id="8.4">
<enabled>true</enabled>
</version>
<version id="1.1">
<enabled>true</enabled>
</version>
</loanRequest>
<shortLoanRequest>true</shortLoanRequest>
<loanRequestWithIssue>true</loanRequestWithIssue>
<loanRequest_8.0>true</loanRequest_8.0>
<deepLinkToConsumerLoan>true</deepLinkToConsumerLoan>
</node>
<node id="node2.online.sberbank.ru">
<loanRequest>
<version id="8.2">
<enabled>true</enabled>
</version>
<version id="8.3">
<enabled>true</enabled>
</version>
<version id="8.4">
<enabled>true</enabled>
</version>
<version id="1.1">
<enabled>true</enabled>
</version>
</loanRequest>
<shortLoanRequest>true</shortLoanRequest>
<loanRequestWithIssue>true</loanRequestWithIssue>
<loanRequest_8.0>true</loanRequest_8.0>
<deepLinkToConsumerLoan>true</deepLinkToConsumerLoan>
</node>
<node id="node3.online.sberbank.ru">
<loanRequest>
<version id="8.2">
<enabled>true</enabled>
</version>
<version id="8.3">
<enabled>true</enabled>
</version>
<version id="8.4">
<enabled>true</enabled>
</version>
<version id="1.1">
<enabled>true</enabled>
</version>
</loanRequest>
<shortLoanRequest>true</shortLoanRequest>
<loanRequestWithIssue>true</loanRequestWithIssue>
<loanRequest_8.0>true</loanRequest_8.0>
<deepLinkToConsumerLoan>true</deepLinkToConsumerLoan>
</node>
</nodes>
</param>
<param name="digitalCreditServices" description="Параметры сервисов функционала">
<type>list</type>
<enabled>true</enabled>
<services>
<service name="ufs.consumer.loan.v1" description="Сервис ЕФС">
<host/>
<path>
consumer-loan/v2/mobile/banking/products/loans/consumerloan/request
</path>
</service>
<service name="PersData" description="Текст виджета условий обработки ПДн">
<host>https://185.157.96.21:443</host>
<path>
consumer-loan/v2/mobile/banking/products/loans/consumerloan/request/GetConfirmationAgreement/
</path>
</service>
</services>
</param>
<param name="CoreAddress" description="Адрес хоста и путь к веб сервису КЛАДР">
<type>service</type>
<enabled>true</enabled>
<services>
<service name="ufs.kladr.v1">
<host>https://185.157.96.21:443</host>
<path>
/loan-suggestion/services/rest/v2/SBOL/Suggestions.KLADR
</path>
</service>
<service name="ufs.kladr.v2">
<host>https://ift.testefs.sberbank.ru/</host>
<path>
/loan-suggestion/services/rest/v2/mobile/Suggestions.KLADR
</path>
</service>
</services>
</param>
<param name="creditCardOrder" description="Заказ кредитной карты в ЕФС">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="creditCardOrderV2" description="Заказ кредитной карты в ЕФС, версия 2">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="creditCardUfsHistory" description="Отображение подробностей по заказу кредитной карты ЕФС в ИО">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="creditCardOrderServices" description="Параметры сервисов функционала заказа кредитной карты в ЕФС">
<type>list</type>
<enabled>true</enabled>
<services>
<service name="persDataAgreement" description="Получение текста условий обработки персональных данных">
<host>https://pfl-psi.efstst.sigma.sbrf.ru:443</host>
<path>
/credit-cards/short-form-capacity/v1/mobile/banking/product/ccard/short-ccard-request/getTextOfAgreementOnTransferInfo
</path>
</service>
</services>
</param>
<param name="UiCaseGibddPenaltySearch" description="Уникальный пользовательский сценарий для поиска штрафов по ВУ/СТС">
<type>list</type>
<nodes>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<serviceID>5000630538</serviceID>
<targetService>5000630916</targetService>
<targetBilling>344</targetBilling>
<targetProvider>5000630916</targetProvider>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<serviceID>622173</serviceID>
<targetService>623095</targetService>
<targetBilling>344</targetBilling>
<targetProvider>623095</targetProvider>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<serviceID>621055</serviceID>
<targetService>621064</targetService>
<targetBilling>344</targetBilling>
<targetProvider>621064</targetProvider>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<serviceID>622173</serviceID>
<targetService>623095</targetService>
<targetBilling>344</targetBilling>
<targetProvider>623095</targetProvider>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<serviceID>621055</serviceID>
<targetService>621064</targetService>
<targetBilling>344</targetBilling>
<targetProvider>621064</targetProvider>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
<serviceID>500202753</serviceID>
<targetService>500413146</targetService>
<targetBilling>284</targetBilling>
<targetProvider>500413146</targetProvider>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
<serviceID>500204565</serviceID>
<targetService>500413943</targetService>
<targetBilling>284</targetBilling>
<targetProvider>500413943</targetProvider>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
<serviceID>387491</serviceID>
<targetService>596879</targetService>
<targetBilling>284</targetBilling>
<targetProvider>596879</targetProvider>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<serviceID>500202753</serviceID>
<targetService>550445849</targetService>
<targetBilling>284</targetBilling>
<targetProvider>550445849</targetProvider>
</node>
</nodes>
</param>
<param name="UiCaseGibddPenaltyPayByUin" description="Уникальный пользовательский сценарий для оплаты штрафов по УИН">
<type>list</type>
<nodes>
<node id="mobile.sberbank.ru">
<enabled>false</enabled>
<serviceID>222222</serviceID>
<targetService>5000630551</targetService>
<targetBilling>344</targetBilling>
<targetProvider>5000630551</targetProvider>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>false</enabled>
<serviceID>617948</serviceID>
<targetService>621822</targetService>
<targetBilling>344</targetBilling>
<targetProvider>621822</targetProvider>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>false</enabled>
<serviceID>618120</serviceID>
<targetService>620678</targetService>
<targetBilling>344</targetBilling>
<targetProvider>620678</targetProvider>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>false</enabled>
<serviceID>617948</serviceID>
<targetService>621822</targetService>
<targetBilling>344</targetBilling>
<targetProvider>621822</targetProvider>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>false</enabled>
<serviceID>618120</serviceID>
<targetService>620678</targetService>
<targetBilling>344</targetBilling>
<targetProvider>620678</targetProvider>
</node>
<node id="node3.online.sberbank.ru">
<enabled>false</enabled>
<serviceID>500202754</serviceID>
<targetService>500413145</targetService>
<targetBilling>284</targetBilling>
<targetProvider>500413145</targetProvider>
</node>
<node id="node2.online.sberbank.ru">
<enabled>false</enabled>
<serviceID>500204566</serviceID>
<targetService>500413942</targetService>
<targetBilling>284</targetBilling>
<targetProvider>500413942</targetProvider>
</node>
<node id="node1.online.sberbank.ru">
<enabled>false</enabled>
<serviceID>387492</serviceID>
<targetService>596878</targetService>
<targetBilling>284</targetBilling>
<targetProvider>596878</targetProvider>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>false</enabled>
<serviceID>500202754</serviceID>
<targetService>550445848</targetService>
<targetBilling>284</targetBilling>
<targetProvider>550445848</targetProvider>
</node>
</nodes>
</param>
<param name="EribNewGibddCatalog" description="Новый каталог Госуслуги, Налоги, Штрафы, Пошлины на замену старого">
<type>list</type>
<nodes>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<catalogID>1526</catalogID>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<catalogID>2428</catalogID>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<catalogID>1526</catalogID>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<catalogID>2428</catalogID>
</node>
</nodes>
<title>Налоги, Штрафы, Пошлины, Бюджетные платежи</title>
</param>
<param name="TPNDataEnrichment" description="Возможность обогащения данных для ТПУ на разрешенных нодах">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="NodeTPNDataEnrichment" description="Возможность обогащения данных для ТПУ на разных нодах">
<type>list</type>
<nodes>
<node id="greenfield0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="enableSMSAllowed" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="aim_ShortTermsView" description="Отображение условий вклада в виде списка при открытии">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="StatementsAndReferences" description="Справки и выписки c v8.1 и более">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>false</enabled>
<statementsHistory>false</statementsHistory>
<statementsPdfViewer>false</statementsPdfViewer>
</node>
<node id="node1.online.sberbank.ru">
<enabled>false</enabled>
<statementsHistory>false</statementsHistory>
<statementsPdfViewer>false</statementsPdfViewer>
</node>
<node id="node2.online.sberbank.ru">
<enabled>false</enabled>
<statementsHistory>false</statementsHistory>
<statementsPdfViewer>false</statementsPdfViewer>
</node>
<node id="node3.online.sberbank.ru">
<enabled>false</enabled>
<statementsHistory>false</statementsHistory>
<statementsPdfViewer>false</statementsPdfViewer>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<statementsPdfViewer>true</statementsPdfViewer>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<statementsPdfViewer>true</statementsPdfViewer>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<statementsPdfViewer>true</statementsPdfViewer>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<statementsPdfViewer>true</statementsPdfViewer>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<statementsPdfViewer>true</statementsPdfViewer>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<statementsPdfViewer>true</statementsPdfViewer>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<statementsPdfViewer>true</statementsPdfViewer>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<statementsPdfViewer>true</statementsPdfViewer>
</node>
<node id="10.21.152.7">
<enabled>true</enabled>
<statementsHistory>true</statementsHistory>
<statementsPdfViewer>true</statementsPdfViewer>
</node>
</nodes>
</param>
<param name="StatementsAndReferences_8_0" description="Справки и выписки v8.0">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>false</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="10.21.152.7">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="StaticSourceMerchantPics" description="">
<link>https://pfm.stat.online.sberbank.ru/PFM/logos/</link>
</param>
<param name="CarLoan" description="Заявка на автокредит">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="CarLoansDetails" description="Карточка автокредита (детализация)">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="CarLoansPayment" description="Пополнение счета по автокредиту">
<type>setting</type>
<enabled>true</enabled>
<refillProvider>623065</refillProvider>
</param>
<param name="CarLoanServices" description="Параметры сервисов функционала">
<type>list</type>
<enabled>true</enabled>
<services>
<service name="PersData" description="Текст виджета условий обработки ПДн">
<host>https://ift.testefs.sberbank.ru/</host>
<path>
/person-credit-mb/v1/mobile/Banking/Products/Loans/CarLoans/Application/GetAgreement
</path>
</service>
</services>
</param>
<param name="UfsRurPayment" description="классические переводы в ЕФС, замена переводов ЕРИБа">
<type>service</type>
<enabled>true</enabled>
</param>
<param name="AccountSpecialCondition" description="Специальные условия по вкладу. Ограничение на максимальную сумму">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="AccountSpecialConditionSum" description="Максимальное значение первоначального взноса, с которого начинает действовать пониженный процент по вкладу">
<currencies>
<currency>
<id>RUB</id>
<maxamount>100000</maxamount>
</currency>
<currency>
<id>OTHER</id>
<maxamount>0</maxamount>
</currency>
</currencies>
</param>
<param name="creditCapacity" description="Кредитный потенциал">
<type>setting</type>
<enabled>true</enabled>
<services>
<service name="persDataAgreement" description="Текст согласия клиента на обработку персональных данных для расчета КП">
<path>
/persDataAgreement/pdp-agreement/v1/CCP_ConfirmationAgreement.html
</path>
</service>
</services>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>false</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
<node id="node1.online.sberbank.ru">
<enabled>false</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
<node id="node2.online.sberbank.ru">
<enabled>false</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
<node id="node3.online.sberbank.ru">
<enabled>false</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>false</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>false</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
<node id="10.21.152.7">
<enabled>true</enabled>
<calculateCreditCapacity>true</calculateCreditCapacity>
<showcase>true</showcase>
<loanApplication>true</loanApplication>
<creditCardApplication>true</creditCardApplication>
</node>
</nodes>
</param>
<param name="Confirmation" description="Модуль подтверждения">
<type>list</type>
<enabled>true</enabled>
<widgetPacks>
<pack id="1">
<enabled>true</enabled>
</pack>
<pack id="2">
<enabled>true</enabled>
</pack>
</widgetPacks>
</param>
<param name="P2PTransferByPhoneToOtherBank" description="Перевод в другие банки по номеру телефона через УЭК">
<type>list</type>
<enabled>true</enabled>
<CustomMessageLimitEnabled>true</CustomMessageLimitEnabled>
<CustomMessageLimit>
Обратите внимание! Доступный лимит для совершения операции составляет
</CustomMessageLimit>
<serviceProviders>
<serviceProvider name="Tinkoff" visibleName="Тинькофф Банк">
<nodes>
<node id="mobile.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>688468</targetProvider>
<targetService>688468</targetService>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>623368</targetProvider>
<targetService>623368</targetService>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>623368</targetProvider>
<targetService>623368</targetService>
</node>
<node id="greenfield1.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>550478249</targetProvider>
<targetService>550478249</targetService>
</node>
<node id="greenfield2.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>500439915</targetProvider>
<targetService>500439915</targetService>
</node>
<node id="node1.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>629175</targetProvider>
<targetService>629175</targetService>
</node>
<node id="node2.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>500446239</targetProvider>
<targetService>500446239</targetService>
</node>
<node id="node3.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>500445546</targetProvider>
<targetService>500445546</targetService>
</node>
<node id="node4.online.sberbank.ru">
<targetBilling>284</targetBilling>
<targetProvider>500439915</targetProvider>
<targetService>500439915</targetService>
</node>
</nodes>
</serviceProvider>
</serviceProviders>
</param>
<param name="cuteChequeDetails" description="Возможность отображения детализированного красивого чека для ТПУ">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="nodeCuteChequeDetails" description="Возможность отображения детализированного красивого чека для ТПУ на разных нодах">
<type>list</type>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="doNotShowPushTutorialForApiLevels" description="Запрет отображения туториала если устройство из черного списка">
<type>list</type>
<enabled>true</enabled>
<APIsCollection>
<API level="23"/>
<API level="22"/>
<API level="21"/>
<API level="19"/>
<API level="17"/>
<API level="16"/>
<API level="15"/>
</APIsCollection>
</param>
<param name="nodeDoNotShowPushTutorialForApiLevels" description="Запрет отображения туториала для устройств входящих в черный список на разных нодах">
<type>list</type>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="pushListAlternativeDesign" description="Возможность отображения альтернативного варианта ленты уведомлений">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="nodePushListAlternativeDesign" description="Возможность альтернативного варианта ленты уведомлений на разных нодах">
<type>list</type>
<nodes>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="UsePushAutoDisable" description="алгоритм автоотключения push">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="PersonalDataProfile" description="Редактирование/добавление персональных данных клиента">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="mobile.sberbank.ru" description="Стенд ПСИ">
<enabled>true</enabled>
<PassportProfile>true</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
<PassportProfile>true</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<PassportProfile>true</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<PassportProfile>true</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<PassportProfile>true</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<PassportProfile>true</PassportProfile>
<EmailProfile>true</EmailProfile>
<PhoneNumberProfile>true</PhoneNumberProfile>
<DriversLicenseProfile>true</DriversLicenseProfile>
<STSProfile>true</STSProfile>
<InnProfile>true</InnProfile>
<SnilsProfile>true</SnilsProfile>
</node>
</nodes>
</param>
<param name="ufsPayments" description="Включает/выключает функционал ефс платежей ">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="HistoryOperation" description="Вкладка История. Блоки работают по логическому ИЛИ">
<type>list</type>
<enabled>true</enabled>
<global/>
<nodes>
<node id="node0.online.sberbank.ru">
<externalOperationForm>false</externalOperationForm>
<historyRefactoredList>false</historyRefactoredList>
<historyRouterEnabled>false</historyRouterEnabled>
<tagAll>false</tagAll>
<showHistorySearch>false</showHistorySearch>
<OmniChannelHistory>false</OmniChannelHistory>
<historyAccountEnabled>false</historyAccountEnabled>
<historyBackendFiltersEnabled>false</historyBackendFiltersEnabled>
</node>
<node id="node1.online.sberbank.ru">
<externalOperationForm>false</externalOperationForm>
<historyRefactoredList>false</historyRefactoredList>
<historyRouterEnabled>false</historyRouterEnabled>
<tagAll>false</tagAll>
<showHistorySearch>false</showHistorySearch>
<OmniChannelHistory>false</OmniChannelHistory>
<historyAccountEnabled>false</historyAccountEnabled>
<historyBackendFiltersEnabled>false</historyBackendFiltersEnabled>
</node>
<node id="node2.online.sberbank.ru">
<externalOperationForm>false</externalOperationForm>
<historyRefactoredList>false</historyRefactoredList>
<historyRouterEnabled>false</historyRouterEnabled>
<tagAll>false</tagAll>
<showHistorySearch>false</showHistorySearch>
<OmniChannelHistory>false</OmniChannelHistory>
<historyAccountEnabled>false</historyAccountEnabled>
<historyBackendFiltersEnabled>false</historyBackendFiltersEnabled>
</node>
<node id="node3.online.sberbank.ru">
<externalOperationForm>false</externalOperationForm>
<historyRefactoredList>false</historyRefactoredList>
<historyRouterEnabled>false</historyRouterEnabled>
<tagAll>false</tagAll>
<showHistorySearch>false</showHistorySearch>
<OmniChannelHistory>false</OmniChannelHistory>
<historyAccountEnabled>false</historyAccountEnabled>
<historyBackendFiltersEnabled>false</historyBackendFiltersEnabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<historyRefactoredList>true</historyRefactoredList>
<historyRouterEnabled>true</historyRouterEnabled>
<tagAll>true</tagAll>
<showHistorySearch>true</showHistorySearch>
<OmniChannelHistory>true</OmniChannelHistory>
<refactoredHistoryDetails>true</refactoredHistoryDetails>
<historyProductEnabled>true</historyProductEnabled>
<historyAccountEnabled>false</historyAccountEnabled>
<historyBackendFiltersEnabled>false</historyBackendFiltersEnabled>
</node>
<node id="mobile.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<historyRefactoredList>true</historyRefactoredList>
<historyRouterEnabled>true</historyRouterEnabled>
<tagAll>true</tagAll>
<showHistorySearch>true</showHistorySearch>
<OmniChannelHistory>true</OmniChannelHistory>
<refactoredHistoryDetails>true</refactoredHistoryDetails>
<historyProductEnabled>true</historyProductEnabled>
<historyAccountEnabled>true</historyAccountEnabled>
<historyBackendFiltersEnabled>true</historyBackendFiltersEnabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<historyRefactoredList>true</historyRefactoredList>
<historyRouterEnabled>true</historyRouterEnabled>
<tagAll>true</tagAll>
<showHistorySearch>true</showHistorySearch>
<OmniChannelHistory>true</OmniChannelHistory>
<refactoredHistoryDetails>true</refactoredHistoryDetails>
<historyProductEnabled>true</historyProductEnabled>
<historyAccountEnabled>false</historyAccountEnabled>
<historyBackendFiltersEnabled>false</historyBackendFiltersEnabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<historyRefactoredList>true</historyRefactoredList>
<historyRouterEnabled>true</historyRouterEnabled>
<tagAll>true</tagAll>
<showHistorySearch>true</showHistorySearch>
<OmniChannelHistory>true</OmniChannelHistory>
<refactoredHistoryDetails>true</refactoredHistoryDetails>
<historyProductEnabled>true</historyProductEnabled>
<historyAccountEnabled>true</historyAccountEnabled>
<historyBackendFiltersEnabled>true</historyBackendFiltersEnabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<historyRefactoredList>true</historyRefactoredList>
<historyRouterEnabled>true</historyRouterEnabled>
<tagAll>true</tagAll>
<showHistorySearch>true</showHistorySearch>
<OmniChannelHistory>true</OmniChannelHistory>
<refactoredHistoryDetails>true</refactoredHistoryDetails>
<historyProductEnabled>true</historyProductEnabled>
<historyAccountEnabled>true</historyAccountEnabled>
<historyBackendFiltersEnabled>true</historyBackendFiltersEnabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<externalOperationForm>true</externalOperationForm>
<historyRefactoredList>true</historyRefactoredList>
<historyRouterEnabled>true</historyRouterEnabled>
<tagAll>true</tagAll>
<showHistorySearch>true</showHistorySearch>
<OmniChannelHistory>true</OmniChannelHistory>
<refactoredHistoryDetails>true</refactoredHistoryDetails>
<historyProductEnabled>true</historyProductEnabled>
<historyAccountEnabled>true</historyAccountEnabled>
<historyBackendFiltersEnabled>true</historyBackendFiltersEnabled>
</node>
<node id="10.21.152.7">
<externalOperationForm>true</externalOperationForm>
<historyRefactoredList>true</historyRefactoredList>
<historyRouterEnabled>true</historyRouterEnabled>
<tagAll>true</tagAll>
<showHistorySearch>true</showHistorySearch>
<OmniChannelHistory>true</OmniChannelHistory>
<refactoredHistoryDetails>true</refactoredHistoryDetails>
<historyProductEnabled>true</historyProductEnabled>
<historyAccountEnabled>true</historyAccountEnabled>
<historyBackendFiltersEnabled>true</historyBackendFiltersEnabled>
</node>
</nodes>
</param>
<param name="geoservice" description="Настройка URL гео-сервисов">
<type>setting</type>
<enabled>true</enabled>
<host>https://geo1.online.sberbank.ru/</host>
</param>
<param name="DDAPermissions" description="Консолидированные включатели функционала Data Driven App">
<type>list</type>
<enabled>true</enabled>
<DdaNodes>
<node id="node0.online.sberbank.ru">
<SmartSearch>true</SmartSearch>
<TransitionToDialog>true</TransitionToDialog>
</node>
<node id="node1.online.sberbank.ru">
<SmartSearch>true</SmartSearch>
<TransitionToDialog>true</TransitionToDialog>
</node>
<node id="node2.online.sberbank.ru">
<SmartSearch>true</SmartSearch>
<TransitionToDialog>true</TransitionToDialog>
</node>
<node id="node3.online.sberbank.ru">
<SmartSearch>true</SmartSearch>
<TransitionToDialog>true</TransitionToDialog>
</node>
<node id="node4.online.sberbank.ru">
<SmartSearch>true</SmartSearch>
<TransitionToDialog>true</TransitionToDialog>
</node>
<node id="greenfield1.online.sberbank.ru">
<SmartSearch>true</SmartSearch>
<TransitionToDialog>true</TransitionToDialog>
</node>
<node id="mobile.sberbank.ru">
<SmartSearch>true</SmartSearch>
<TransitionToDialog>true</TransitionToDialog>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<SmartSearch>true</SmartSearch>
<TransitionToDialog>true</TransitionToDialog>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<SmartSearch>true</SmartSearch>
<TransitionToDialog>true</TransitionToDialog>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<SmartSearch>true</SmartSearch>
<TransitionToDialog>true</TransitionToDialog>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<SmartSearch>true</SmartSearch>
<TransitionToDialog>true</TransitionToDialog>
</node>
</DdaNodes>
</param>
<param name="P2PTransferPDV" description="Рубильники для функционала Переводов До Востребования">
<type>list</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>false</enabled>
<demandTransfer>false</demandTransfer>
<changeDemandTransfer>false</changeDemandTransfer>
<stornoDemandTransfer>false</stornoDemandTransfer>
<selfTransfer>false</selfTransfer>
<selfTransferStorno>false</selfTransferStorno>
</node>
<node id="node1.online.sberbank.ru">
<enabled>false</enabled>
<demandTransfer>false</demandTransfer>
<changeDemandTransfer>false</changeDemandTransfer>
<stornoDemandTransfer>false</stornoDemandTransfer>
<selfTransfer>false</selfTransfer>
<selfTransferStorno>false</selfTransferStorno>
</node>
<node id="node2.online.sberbank.ru">
<enabled>false</enabled>
<demandTransfer>false</demandTransfer>
<changeDemandTransfer>false</changeDemandTransfer>
<stornoDemandTransfer>false</stornoDemandTransfer>
<selfTransfer>false</selfTransfer>
<selfTransferStorno>false</selfTransferStorno>
</node>
<node id="node3.online.sberbank.ru">
<enabled>false</enabled>
<demandTransfer>false</demandTransfer>
<changeDemandTransfer>false</changeDemandTransfer>
<stornoDemandTransfer>false</stornoDemandTransfer>
<selfTransfer>false</selfTransfer>
<selfTransferStorno>false</selfTransferStorno>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>false</enabled>
<demandTransfer>false</demandTransfer>
<changeDemandTransfer>false</changeDemandTransfer>
<stornoDemandTransfer>false</stornoDemandTransfer>
<selfTransfer>false</selfTransfer>
<selfTransferStorno>false</selfTransferStorno>
</node>
<node id="greenfield2.online.sberbank.ru">
<enabled>false</enabled>
<demandTransfer>false</demandTransfer>
<changeDemandTransfer>false</changeDemandTransfer>
<stornoDemandTransfer>false</stornoDemandTransfer>
<selfTransfer>false</selfTransfer>
<selfTransferStorno>false</selfTransferStorno>
</node>
<node id="194.186.207.23">
<enabled>false</enabled>
<demandTransfer>false</demandTransfer>
<changeDemandTransfer>false</changeDemandTransfer>
<stornoDemandTransfer>false</stornoDemandTransfer>
<selfTransfer>false</selfTransfer>
<selfTransferStorno>false</selfTransferStorno>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
<demandTransfer>true</demandTransfer>
<changeDemandTransfer>true</changeDemandTransfer>
<stornoDemandTransfer>true</stornoDemandTransfer>
<selfTransfer>true</selfTransfer>
<selfTransferStorno>true</selfTransferStorno>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
<demandTransfer>true</demandTransfer>
<changeDemandTransfer>true</changeDemandTransfer>
<stornoDemandTransfer>true</stornoDemandTransfer>
<selfTransfer>true</selfTransfer>
<selfTransferStorno>true</selfTransferStorno>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
<demandTransfer>true</demandTransfer>
<changeDemandTransfer>true</changeDemandTransfer>
<stornoDemandTransfer>true</stornoDemandTransfer>
<selfTransfer>true</selfTransfer>
<selfTransferStorno>true</selfTransferStorno>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<demandTransfer>true</demandTransfer>
<changeDemandTransfer>true</changeDemandTransfer>
<stornoDemandTransfer>true</stornoDemandTransfer>
<selfTransfer>true</selfTransfer>
<selfTransferStorno>true</selfTransferStorno>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
<demandTransfer>true</demandTransfer>
<changeDemandTransfer>true</changeDemandTransfer>
<stornoDemandTransfer>true</stornoDemandTransfer>
<selfTransfer>true</selfTransfer>
<selfTransferStorno>true</selfTransferStorno>
</node>
<node id="10.21.152.7">
<enabled>true</enabled>
<demandTransfer>true</demandTransfer>
<changeDemandTransfer>true</changeDemandTransfer>
<stornoDemandTransfer>true</stornoDemandTransfer>
<selfTransfer>true</selfTransfer>
<selfTransferStorno>true</selfTransferStorno>
</node>
</nodes>
</param>
<param name="collect_statistics" description="">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="biometryAgreement" description="Включает/выключает функционал сбор согласия на биометрию">
<type>list</type>
<enabled>true</enabled>
<showTutorial>true</showTutorial>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="LoanNavigationScreenEnabled" description="Разводной экран для кредитных продуктов">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="MAppDebitCardNegativeBalance" description="Почему минус на дебетовой карте">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="P2PReceiverPhonePriorityCard" description="Установка приоритетной карты для зачисления P2P Переводов по НМТ">
<type>setting</type>
<enabled>true</enabled>
</param>
<param name="MAppNewBlockCardProcess" description="Обновленный процесс блокировки карт">
<type>service</type>
<enabled>true</enabled>
<nodes>
<node id="node0.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node2.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="node3.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="greenfield1.online.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="mobile.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node1-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode2.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="psinode1.testonline.sberbank.ru">
<enabled>true</enabled>
</node>
<node id="194.186.207.23">
<enabled>true</enabled>
</node>
</nodes>
</param>
<param name="VoiceControl" description="Голосовое управление в мобильном приложении">
<type>list</type>
<enabled>true</enabled>
<CountRepeat>3</CountRepeat>
<nodes>
<node id="node0.online.sberbank.ru">
<voice>false</voice>
<search>false</search>
<voiceInSmartSearch>true</voiceInSmartSearch>
</node>
<node id="node1.online.sberbank.ru">
<voice>false</voice>
<search>false</search>
<voiceInSmartSearch>true</voiceInSmartSearch>
</node>
<node id="node2.online.sberbank.ru">
<voice>false</voice>
<search>false</search>
<voiceInSmartSearch>true</voiceInSmartSearch>
</node>
<node id="node3.online.sberbank.ru">
<voice>false</voice>
<search>false</search>
<voiceInSmartSearch>true</voiceInSmartSearch>
</node>
<node id="greenfield1.online.sberbank.ru">
<voice>false</voice>
<search>true</search>
<voiceInSmartSearch>true</voiceInSmartSearch>
</node>
<node id="194.186.207.23">
<voice>false</voice>
<search>true</search>
<voiceInSmartSearch>true</voiceInSmartSearch>
</node>
<node id="mobile.sberbank.ru">
<voice>false</voice>
<search>true</search>
<voiceInSmartSearch>true</voiceInSmartSearch>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<voice>true</voice>
<search>true</search>
<voiceInSmartSearch>true</voiceInSmartSearch>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<voice>false</voice>
<search>true</search>
<voiceInSmartSearch>true</voiceInSmartSearch>
</node>
</nodes>
</param>
<param name="interTransfer" description="Перевод для получения наличных в Western Union">
<type>list</type>
<enabled>true</enabled>
<serviceProviders>
<serviceProvider name="Western Union" visibleName="Western Union">
<nodes>
<node id="ift-node1-mp.testonline.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>623372</targetProvider>
<targetService>623372</targetService>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<targetBilling>344</targetBilling>
<targetProvider>622310</targetProvider>
<targetService>622310</targetService>
</node>
</nodes>
</serviceProvider>
</serviceProviders>
</param>
<param name="EribStatePaymentShortCuts" description="Каталог бюджетных платежей - быстрый доступ к популярным услугам">
<type>list</type>
<shortcuts>
<shortcut>
<title>Штрафы ГИБДД</title>
<icon>
https://stat.online.sberbank.ru/PhizIC-res/logos/PU/7707089101.jpg
</icon>
<nodes>
<node id="ift-node1-mp.testonline.sberbank.ru">
<catalogID>621055</catalogID>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<catalogID>621055</catalogID>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<catalogID>621055</catalogID>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<catalogID>621055</catalogID>
</node>
</nodes>
</shortcut>
<shortcut>
<title>Оплата налога</title>
<icon>
https://stat.online.sberbank.ru/PhizIC-res/IMG/PU/20/63/61/2b26d928c6b985710071f62251_38347.jpg
</icon>
<nodes>
<node id="ift-node1-mp.testonline.sberbank.ru">
<catalogID>615397</catalogID>
</node>
<node id="ift-node2-mp.testonline.sberbank.ru">
<catalogID>615397</catalogID>
</node>
<node id="ift-node1.testonline.sberbank.ru">
<catalogID>615397</catalogID>
</node>
<node id="ift-node2.testonline.sberbank.ru">
<catalogID>615397</catalogID>
</node>
</nodes>
</shortcut>
</shortcuts>
</param>
</params>
</configuration>
