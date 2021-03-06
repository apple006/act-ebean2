# act-ebean2 CHANGELOG

1.6.2 - 02/Mar/2018
* update act to 1.8.5
* update ebean to 11.15.3

1.6.1 - 25/Mar/2018
* rename package from `act.ebean2` to `act.ebean`

1.6.0 - 25/Mar/2018
* rename to act-ebean
* update act to 1.8.2
* update act-sql-common to 1.3.2
* update ebean to 11.15.1

1.5.1 - 11/Mar/2018
* update to act-1.8.1
* update to act-sql-common-1.3.1
* update to ebean-11.14.3

1.5.0 - 4/Mar/2018
* update to act-1.8.0
* update to ebean-11.13.1
* Support act timestamp annotation #19

1.4.0
* update to act-1.7.0

1.3.0
* update to act-1.6.5
* update act-sql-common to 1.2.1
* update ebean to 11.9.1

1.2.1
* add `@BindOn` annotation to `EbeanConfigLoaded` event to allow early binding of listeners

1.2.0
* update act to 1.6.0
* update act-sql-common to 1.2.0

1.1.5
* update act to 1.5.1
* update act-sql-common to 1.1.3
* update ebean to 11.5.1

1.1.2
* update to act-1.4.11, act-sql-common-1.1.1
* apply oslg-bootstrap version mechanism
* improve maven build process

1.1.1
* Don't provide `EbeanServer` to `EbeanDao` if it is already provided #12 
* Suppress warning `cannot find job by id: __act_app__db_svc_loaded` #11 

1.1.0
* catch up to act-1.4.0, act-sql-common-1.1.0

1.0.4
- NPE when no third party datasource configured #6 
- update act-sql-common to 1.0.2

1.0.3
- update act-sql-common to 1.0.1
- It doesn't start with MySQL jdbc driver 5.x #3 
- Ebean Agent loaded twice if there are two ebean db services #4
- The datasource created in sql-common not used when creating ebean server #5 

1.0.2
- does not work when app start in PROD mode #2 

1.0.1
- It should use ebean's naming convention by default #1 

1.0.0 - baseline version
