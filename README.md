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
## add info / fill profile
```sh
{
    fullName: string,
    nickname: string,
    dateOfBirth: Date,
    phoneNumber: number,
}
```

## Buy premium
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

### notification sound 
```sh
{
    notification_id: number,
    sound: boolean
}
```
### notification vibration
```sh
{
    notification_id: number,
    vibration: boolean,
}
```
### notification hints
```sh
{
    notification_id: number,
    hints: boolean,
}
```
### notification updates and news
```sh
{
    notification_id: number,
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
## Create article
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
## Subscribe / add to friends 
```sh
{
    user_id: number,
    ban_user_id: number,
}
```
## blacklist / ban 
```sh
{
    user_id: user_id,
    subscription: user_id,
}
```
## Security settings
### face ID 
```sh 
{
    user_id: id,
    face_id: boolean
}
```
### "remember me" 
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
## add to bookmarks 
```sh 
{
    blog_id: id,
    user_id: id
}
```
## like 
```sh 
{
    blog_id: id,
    like: boolean
}
```

