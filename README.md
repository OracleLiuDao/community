## 六道社区
2019年12月18日23:43:55 持续更新ing
##资料
[添加github登录功能OAuth](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)
##用到的网址
[githubAPI](https://developer.github.com/apps/building-oauth-apps/authorizing-oauth-apps/)
##脚本
```sql
create table USER
(
    ACCOUNT_ID   VARCHAR(100),
    NAME         VARCHAR(50),
    TOKEN        CHAR(36),
    GMT_CREATE   BIGINT,
    GMT_MODIFIED BIGINT,
    ID    int     INTEGE auto_increment,
    constraint USER_PK
        primary key (ID)
);
```
