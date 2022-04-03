# PairPro
---

### A place for coding enthusiasts to chat with like-minded people and find a partner for a session of pair programming!
---

![home page](/screenshots/home.png)


<details>
  <summary>Click for more screenshots</summary>

  ![register page](/screenshots/register.png)
</details>
</br>


## Usage
---
### Visit
---
### PairPro is deployed on Heroku and can be visited [here](https://be-a-pair-pro.herokuapp.com/).
  You can sign up yourself, or you can be Bob for the day:

  |email | password |
  |---|---|
  |bob@example.com | PairProForLife | 

### Run Locally
---
You will need your own [MongoDB connection string](https://www.mongodb.com/docs/guides/cloud/connectionstring/).
Clone this directory, then in the root folder:
```
$ cp env.example .env
```
Update .env with your details.
```
$ yarn
$ cd client
$ yarn
$ cd ..
$ yarn dev
```
### Run Tests
---
```
$ cd client
$ yarn test
```

<br>

## Development
---
This was created as a group project at the end of our [Makers](http://makers.tech/) Bootcamp journey.


<details>
  <summary>Click for a full list of User Stories</summary>

  ---
  ### MVP User Stories
  ---
  ```
  As a user,
  So I can access the pair programming website,
  I would like to sign up.
  ```
  ```
  As a user, 
  So my profile can be remembered,
  I would like to sign in.
  ```
  ```
  As a user,
  So I can keep my profile safe,
  I would like to sign out. 
  ```
  ```
  As a user, 
  So that I can see other programmers to pair with,
  I would like to see a list of users.
  ```
  ```
  As a user, 
  So other users know if we share a language,
  My profile will contain the technologies I use.
  ```
  ```
  As a user,
  So that others can decide whether they want to work with me, 
  I can state on my profile the things I’d like to pair on etc.
  ```
  ```
  As a user,
  So other users can see my past projects,
  My profile will link to my GitHub.
  ```
  ```
  As a user, 
  So I can arrange a session with other members, 
  I would like to be able message other members.
  ```
  ---
  ### Nice To Have User Stories - Completed
  ---
  ```
  As a user, 
  So I can find members with relevant interests,
  I want to filter by language, level or location/remote.
  ```
  ```
  As a user,
  So the website feels a bit more personal, 
  I want to have a profile picture.
  ```
  ```
  As a user, 
  So I can message people in real-time, 
  I would like a chat-feature.
  ```
  ---
  <details>
    <summary>Nice To Have User Stories - Future Prospects</summary>

  ```
  As a user,
  So the website feels less wordy and a bit more colourful to the eye,
  I want to see the respective language icon next to each coding language
  ```
  ```
  As a user
  So I can stay connected with other members
  I would like to add friends to my account
  ```
  ```
  As a user, 
  So I can arrange spontaneous pairing sessions, 
  I would like to see who of my friends is online.
  ```
  ```
  As a user, 
  So we can code directly on the website without having to open VScode, 
  I would like VScode integration.
  ```
  ```
  As a user,
  So I can share my skills and see other people’s ‘skills’,
  I would like to endorse other members e.g. ‘is punctual’, ‘has good chat’
  ```
  ```
  As a user, 
  So I can directly pair program via a Zoom, 
  I would like Zoom integration on the website.
  ```
  ```
  As a user, 
  So that I can have an easy sign-in process and automatically link my accounts, 
  I would like the option to sign-up with github/linkedin.
  ```
  ```
  As a user,
  So that I can show that I have completed tasks,
  I would like badges to be added to my profile
  ```
  </details>
</details>