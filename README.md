# xenforo
XenForo API library


#### Api.find_name(username)
Get user object by username

Return [tye user](https://xenforo.com/community/pages/api-endpoints/#type_User) || None


#### Api.find_email(email)
Get user object by email

Return list, [type user](https://xenforo.com/community/pages/api-endpoints/#type_User) || None
|

#### Api.users(page)
Get dict users of PAGE

Return dict, username:id


#### Api.user(username, password, email)
Create user

Return boolean


#### Api.avatar(username, path_to_file)
Add user avatar from path

Return boolean