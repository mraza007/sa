## App description

A social platform in the form of an **imageboard**.

### Definition
As per Wikipedia's definition: *An imageboard is a type of internet forum which operates mostly via posting images*. This posting is possible without the need of registering an account.

### Concept
Imageboards are divided in sections called **boards**. This boards may be of any niche, for example there may be a *history* board for discussion and posting of images related to world history.
Imageboards aren't strictly for posting images, there may be a *Programming Help* board for posting questions and answers related to programming problems a la stackoverflow.

What boards there actually will be is to be discussed after developing the core application.

Posts created on boards are to be called **topics**. A topic consists of one or more **file(s)**, which must be images, a **title**, **message body**, and optionally an **author** for users who which to be identified by a name. 
Posts may receive a limited amount of replies, this replies consist of one or more **files** and a **message body**.
Together, the topics and its replies constitude a **thread**.

### Administration
There must be an option for administrators to create, edit and delete boards as they please.

There must be an option for administrators to delete topics and or any of its replies in the case that it breaks a certain site rule. This rules must include prohibition to post topics with illegal material such as explicit images of underage and terrorist propaganda (this are actually common problems in any user-generated website, that may get your site shutdown if you don't take action soon enough).

There must be an option for administrators to control when users can or can not post on this boards, for example there could be an option to set a specific board on *read-only* mode. This could be useful in case of mantainance.

### Designing the Api 

#### URL Routes
- `http://appname/boards/user/image`
- `http://appname/boards/user/title`
- `http://appname/boards/user/comments`
- `http://appname/boards/user/message`

#### Frameworks for building an API.
- Flask
- Go
- Django
- Nodejs
