# Приложение для обзора технических средств по компонентному анализу
Приложение разработано в рамках разработки дипломной работы на тему "Разработка безопасного программного обеспечения. 
Защита приложений от Атак на цепи поставок при использовании компонентов с открытым исходным кодом".

Приложение не несет в себе никакой полезной ценности и предназначено исключительно для тестирования программных средств 
по поиску уязвимостей в используемых компонентах.

# Компоненты и ожидаемые уязвимости
| Компонент | CVE <br/>(Или аналог) | CVS | CVSS <br/>version
| --------- | -----------------| ---- | ---- |
| com.fasterxml.jackson.core:jackson-databind:2.9.10.5 
| | CVE-2020-24616 | 8.1 | 3.1
| | CVE-2020-24750 | 8.1 | 3.0
| | CVE-2020-25649 | 7.5 | 3.0
| commons-io:commons-io:2.0 | sonatype-2018-0705 | 7.8 | 3.0
| org.apache.tomcat.embed:tomcat-embed-core:9.0.39 | CVE-2020-17527 | 7.5 | 3.1
| com.google.guava:guava:24.0-jre | CVE-2018-10237 | 5.9 | 3.1
| org.bouncycastle:bcprov-jdk16:1.46 
| | CVE-2018-1000613 | 9.8 | 3.0
| | CVE-2018-5382 | 9.8 | 3.0
| | CVE-2016-1000338 | 7.5 | 3.0
| | CVE-2016-1000342 | 7.5 | 3.0
| | CVE-2016-1000343 | 7.5 | 3.0
| | CVE-2016-1000352 | 7.4 | 3.0
| | CVE-2016-1000344 | 7.4 | 3.0
| | CVE-2016-1000341 | 5.9 | 3.0
| | CVE-2016-1000345 | 5.9 | 3.0
| | CVE-2017-13098 | 5.9 | 3.0
| | CVE-2016-1000339 | 5.3 | 3.0
| | CVE-2015-7940 | 5.0 | 2.0
| | CVE-2013-1624 | 4.0 | 2.0
| | CVE-2016-1000346 | 3.7 | 3.0
| | CVE-2015-6644 | 3.3 | 3.0
| org.springframework:spring-web:3.0.5 | 
| | CVE-2020-5398 | 7.5 | 3.1 |
| | CVE-2014-0225 | 8.8 | 3.0
| | CVE-2013-4152 | 6.8 | 2.0
| | CVE-2014-0054 | 6.8 | 2.0
| | CVE-2016-1000027 | 9.8 | 3.1 |
| org.springframework.boot:spring-boot:2.0.0.M6 | CWE-79 | 6.1 | 3.0 |
|org.apache.struts:struts2-core:2.3.30
| | CVE-2017-5638 | 10.0 | 3.0 |
| | CVE-2018-11776 | 9.8 | 3.0 |
| | CVE-2017-9791 | 9.8 | 3.1 |
| | CVE-2016-6795 | 9.8 | 3.1 |
| | CVE-2017-9805 | 8.1 | 3.1 |
| | CVE-2017-9787 | 7.5 | 3.1 |
| | CVE-2018-1327 | 7.5 | 3.1 |
| commons-fileupload:commons-fileupload:1.3.2 | CVE-2016-1000031 | 9.8 | 3.1 |
| org.apache.struts:struts-core:1.3.10 | CVE-2012-1007 | 4.5 | 2.0
| commons-beanutils:commons-beanutils:1.8.0 
| | CVE-2014-0114 | 7.5 | 2.0
| | CVE-2019-10086 | 7.3 | 3.1



# Сборка
* windows: `gradlew.bat build`
* unix: `./gradlew build`
# Автор
| Баранюк Иван Сергеевич | https://github.com/pctF |
| ---- | ----
