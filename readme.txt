
#user_channel_authentication
drop table if exists user_channel_authentication;
CREATE TABLE  user_channel_authentication(
id                    bigint,
id_card_num           string,
id_card_name          string,
id_card_date          bigint,
province              bigint,
city                  bigint,
district              bigint,
address               string,
weixin_no             string,
id_card_no_date       int,
create_time           bigint,
audit_status          int,
audit_view            string,
audit_time            bigint,
user_id               bigint,
contact_mobile        string
)
;


#花生小店渠道 user_store_member
drop table if exists user_store_member;
CREATE TABLE  user_store_member(
id                    bigint,
user_mobile           string,
user_status           int,
create_time           bigint,
online_user_id        bigint,
company_id            bigint,
operator_id           bigint,
channel_id            bigint
)
;