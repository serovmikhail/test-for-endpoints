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
