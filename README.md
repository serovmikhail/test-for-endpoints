# Endpoints
## registration
```sh
{
    email: string,
    password: string,
    gender: ?(enum),
    interests: ?(enum)
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
```
## Buy premium/премиум подписка
```sh
{
    user_id:id,
    subscription_type: boolean
}
```
## feedback

```sh
{
    feedback_id: number,
    user_name: string,
    email: string,
    message: string
}
```

## notification management

```sh
{
    notifications_id: number,
    sound: boolean,
    vibration: boolean,
    hints: boolean,
    updates_and_news: boolean
}
```

## view chats

```sh
{
    contact_list_id: number,
    chat_id: number
}
```

## to write a message

```sh
{
    chat_id: number,
    message: string,
    date: string,
    attachmentlds: string,
    user_id: string
}
```

## song

```sh
{
    song_id: number,
    song: string,
    author: string
}
```

## playlist

```sh
{
    playlist_id: number,
    title: string,
    song_id: number,
    bookmark: boolean
}
```
## Create article/ Создать статью
```sh
{
    title: string,
    content: string,
    date: Date,
    article category: ? | enum,
    photo: ?,
    author_id: user_id,
}
```
## Subscribe/ подписаться на других пользователей
```sh
{
    user_id: user_id,
    ban_user_id: user_id,
}
```
## blacklist/ban / заблокировать других пользователей
```sh
{
    user_id: user_id,
    subscription: user_id,
}
```
## Настройка безопасности/ Безопасность
### face ID 
```sh 
{
    user_id: id,
    face_id: boolean
}
```
### "Запомнить меня" 
```sh 
{
    user_id: id,
    remember_user: boolean
}
```
### Touch ID 
```sh 
{
    user_id: id,
    touch_id: boolean
}
```
## добавить в закладки 
```sh 
{
    blog_id: id,
    user_id: id
}
```
### like / лайк * 
```sh 
{
    blog_id: id,
    like: boolean
}
```

