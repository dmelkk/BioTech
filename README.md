# BioTech
Git for BioTech Hackathon

Обозначить пролему

Что упомянуть:
-уменьшит число информационных контактов и посредников
-исключаем человеческий фактор
-отпадает необходимость траты на проверку днк и используется метод проверки хэш сумм
-изи чекинг через смартфон
-децентрализованное хранение данных
-всегда остается возможность проверить днк
-инфа о доставке в кркоде
-time stamp contract
-пересылаешь бабки когда прошла проверка
-брак отсылаем обратно
-платишь если транзакция прошла успешно

для каждого пакета создается последовательная цепь точек, с проверкой, чтобы знать где товар проебался

Вот главные моменты, которые вам необходимо будет предусмотреть:

Аннотация (до 1 страницы) – письменное обращение для высшего руководств.

**Hello, everyone! We are the team "ZBC" and we want to present our view of supply chain for every marked product** 

Резюме (1-3 страницы) – основная информация, для ознакомления с бизнес–планом.

**Our presentation contains 3 main topics. First of all, we will tell about the problem we are going to solve. Then, we are going to speak about our solution. And, finally, we will compare our technology with simmilar popular companies projects.**
 
##Problem

**So let's start.** 
**We asked ourselves: How can we reduce the cost of DNA-tags checking? And: What if transactions could be verified, recorded and coordinated autonomously without third parties? If this could be done, it would eliminate an entire layer of complexity from our global supply chains. So we would like to offer another solution for such problems**

as we know each dna sample examination is expensive, and checkinig of all dilivery parts is impossible because of financial side. Instead of checking every product of supply we introduce next sequencing:
It is normal situation that before the raw material gets on the counter as final products it has a lot of stadies in different factories. For example, T-shirts:
Raw material supply
Raw material processing
Create fabric for the product
Product tailoring

Between all we introduce smartcontracts. And to provide the information that every step was succsessfully passed we are logging the result of each smartcontract into blockchain. For now, stores can easily check all information about products they sell. One the other hand, if there are any problems on any step of supplying to the store, top management can easily track at what stage the process has failed

##Solution

**This is the promise blockchain presents to the logistics
industry. Right now, this technology is still far from
maturity with many challenges to overcome before
it can be successfully deployed at scale in the logistics
industry. Likely the biggest challenge will be in achieving
successful industry adoption through collaboration
and even coopetition between diverse supply chain
stakeholders that have legacy processes and varying
interests.**

But early applications of this emerging technology across
a number of industries – from finance to energy, and
manufacturing to retail – suggest blockchain has a
favorable chance of achieving its full potential in future.
When it does, this technology will facilitate greater
efficiency and new business models including faster and
leaner global trade logistics, superior transparency and
traceability in the supply chain, and increased automation
of commercial processes in logistics**

so we chose open source Etherium based blockchain for our project, that mostly saticfide 
all our needs. The basic idea is preaty simple: it's a main blockchain the consists subchains 
of smartcontracts between participients of supply chain.

let's dive dipper in to the this procec.
First of all we have factory who marks thair produckt with DNA-Sample, then factory supllying further.
It's the main point of our idea. We creating time stamp smart contract about this deal then we add some 
important information adout product (like DNA-Sample hash) if contract was successful than we push in Blockchain. If it wasn't, Product would be send back with obvious consequences. In this way the last end-consumer, but also everyone in the supply chain, know everything about origins of a product. So we avoid unnecessary DNA-Sample verifications wich is very ecpensive, but it is still posible.

##Another existing solutions

There are a lot of logistics companies all over the world, and some of them already use the blockchain technology. For example, such British companies as Martin Yarlgaard and Everlegger label their products with qr-codes and enter the results of certification checks into blocks at the each stage. But what do we offer? We Offering our implementation, we are the first one who introduces DNA markers and blockchain at the same time. Furthemore, compared to the above companies, helps to avoid code falsification better and completely trace at which stage the potential supply of raw materials failed.

Бизнес–план (45-60)  — для подробного изучения проекта специалистами инвестора и экспертами.

Резюме
Цель бизнес-плана.



Потребность в финансах, для каких целей они необходимы.
Краткое описание бизнеса и его целевого клиента.
Основные отличия от конкурентов.
Основные финансовые показатели.

1. Цели и задачи

Здесь вам нужно будет привести анализ идеи (SWOT–анализ). Раскрыть сильные и слабые стороны, а также возможности и угрозы.

Анализ идеи.
Цель деятельности (чего вы хотите достичь).
Характеристика отрасли.
2. Продукт (услуга)

Важно, чтобы эта часть была написана ясным, четким языком, понятным для неспециалиста.

Описание продукции или услуги и их применение.
Уникальность
Необходимые для бизнеса технологии и квалификация.
Лицензия/патентные права.
3. Анализ рынка

Рынок и маркетинг —  решающий фактор для всех компаний. Вам необходимо предварительно собрать и  обработать большой объём «черновой» информации.

Покупатели.
Конкуренты (их сильные и слабые стороны).
Сегменты рынка.
Размер рынка и его рост.
Оценочная доля на рынке.
Состав вашей клиентуры.
Влияние конкуренции.
4. План маркетинга

На этом этапе основная задача – завоевать доверие и расположение потенциального инвестора. Если у вас нет специального образования, следует почитать книги по маркетингу, обратиться к специалисту.

Маркетинговая расстановка (основные характеристики продукции, услуги в сравнении с конкурентами).
Ценообразование (как правильно установить цену на товар).
Схема распространения товаров.
Методы стимулирования продаж.
5. План производства

Здесь вы должны рассмотреть все вопросы, связанные с помещениями, которые вы занимаете, их расположением, оборудованием, персоналом.

Расположение помещений.
Оборудование.
Источники поставки основных материалов и оборудования.
Использование субподрядчиков.
6. Управленческий персонал

Инвестиции делаются в конкретных людей, а не в бизнес–план, потому данный раздел является одним из самых важных.

Основной руководящий состав.
Состав персонала.
Вознаграждение.
7. Источники и объём требуемых ресурсов

В этом разделе вы должны представить свои соображения относительно:

Объем требуемых средств.
Источники их получения, форма, сроки.
Сроки возврата средств.
8. Финансовый план и анализ рисков

Деловые люди делятся на тех, кто любит работать с цифрами, и кто боится их. Для тех, кто относится к первой категории, этот раздел бизнес–плана, несомненно, самый важный.

Объем продаж, прибыль, себестоимость и т.д.
Риски, и каким образом их можно избежать.
9. Детальный финансовый план

Вам необходимо включить в свой бизнес–план детальный финансовый план:

Прогноз объемов продаж.
Оценки прибыли и убытков.
Анализ движения наличности (ежемесячно на первый год, затем поквартально).
Годовая балансовая ведомость.
И напоследок, хотелось бы дать несколько полезных советов по составлению бизнес–плана:

Для начала почитайте несколько других бизнес–планов.
Бизнес–план должен отражать вашу индивидуальность.
Подготовка бизнес–плана  — это работа, требующая подключения воображения.
Набирайтесь опыта и навыков в выбранном направлении.
Пишите только в те дни, когда вы полны энергии, а не когда вы морально и физически истощены.
