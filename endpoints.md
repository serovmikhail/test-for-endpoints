# Endpoints
## registration
```sh
{
    email: string,
    password: string,
    gender: ?(enum),
    interests: ?(enam)
}
```
## login
```sh
{
    email: string,
    password: string
}
```
## add info/заполнить профиль
```sh
{
    fullName: string,
    nickname: string,
    dateOfBirth: Date,
    phoneNumber: number,
}
```
## Buy premium/премиум подписка
```sh
{
    user_id:id,
    subscription_type: boolean
}
```
## Buy premium/премиум подписка
```sh
{
    user_id:id,
    subscription_type: boolean
}
```
