
<!-- CUSTOMGPT -->
# CustomGPT

CustomGPT is a ChatGPT Clone that's displayed in a chatbot like environment that uses OpenAI's API gpt-3.5-turbo to get the response of each message in the chat.

</br>

<!-- GETTING STARTED -->
## Getting Started

Before you can use this you need to have an account with OpenAI and create a new API KEY.

You can create an account with OpenAI [Here](https://platform.openai.com/)

Once you sign up you can now create a new API KEY [Here](https://platform.openai.com/account/api-keys)

Save that API KEY for now we will use this later.

</br>

<!-- INSTALLATION -->
## Installation

1. Clone the repo

    ```bash
    git clone https://github.com/royshemtov13/CustomGPT.git
    ```

2. install npm packages

    ```bash
    npm install
    ```

3. Create a .env file in the repo and insert the API KEY as follows

    ```bash
    VITE_API_KEY="ENTER HERE"
    ```

Great! You're all set

</br>

<!-- USAGE -->
## Usage

once you have all that set and done you can run your app

```bash
npm run dev
```

you will recieve something that looks like this

```bash
$ npm run dev

> app@0.0.0 dev
> vite


  VITE v4.1.4  ready in 672 ms

  ➜  Local:   http://127.0.0.1:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help
```

open this http link there you will see that ChatBot App.

Now you can interact with it and ask it anything you would like to know that's in his scope of answering.

</br>

<!-- ADVANCED USAGE -->
## Change CustomGPT behavior

By default CustomGPT will behave like the regular ChatGPT bot

But if you want you can change CustomGPT's response behavior. Hense the name "CustomGPT"

You can do that by going to the ```App.jsx``` file and in line 18 you can insert to the content key new values.

For example:

```jsx
16. const systemMessage = {
17. role: "system",
18. content: "Behave like you are a pirate", // This Line here
19. };
```

Given that example CustomGPT will now become PirateGPT and will answer questions as if it is a now a Pirate! A PirateGPT bot.

<!-- EXAMPLE -->
## Example

![image](src/assets/example.png)

</br>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

</br>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.
