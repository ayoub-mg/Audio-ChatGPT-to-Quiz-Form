# Audio-ChatGPT-to-Quiz-Form

A powerful tool that leverages the GPT-3.5 language model to create quizzes on any topic of your choice, based on au audion prompt input. This application is built using Python and Streamlit, making it easy to create, customize, and share quizzes with others.


**Author** : MARZOUG Ayoub.

  

https://github.com/ayoub-mg/Audio-ChatGPT-to-Quiz-Form/assets/92301593/5f890fd3-175c-4b10-82ad-406b1522e20b

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Obtaining OpenAI API Keys](#obtaining-openai-api-keys)
- [Setting Secrets](#setting-secrets)
- [Executing the App](#executing-the-app)
- [Contributing](#contributing)
- [License](#license)

## Requirements

To use the Quiz Generator, you need the following:

- Python 3.10 or higher
- An OpenAI API key to access GPT-3.5

## Installation

1. Clone the repository to your local machine:

```
git clone https://github.com/ayoub-mg/Audio-ChatGPT-to-Quiz-Form.git
```

2. Change to the project directory:

```
cd Audio-ChatGPT-to-Quiz-Form
```

3. Create a virtual environment and activate it:

```
python3 -m venv ayoub
source ayoub/bin/activate
```

Alternatively, you can use `conda` to create a virtual environment:

```
conda create -n ayoub python=3.9
conda activate ayoub
```

4. Install the required packages from `requirements.txt`:

```
pip install -r requirements.txt
```

## Obtaining OpenAI API Keys

To obtain the necessary API key and organization from OpenAI, follow these steps:

1. Go to the [OpenAI website](https://www.openai.com/).
2. If you don't have an account, click "Sign up" and create one.
3. Once logged in, navigate to the [API key management page](https://platform.openai.com/account/api-keys).
4. Click "Create new secret key" and note down the generated API key (you would not see the key again).
5. On the same page, find your organization ID under the "Settings" section.

You now have the API key and organization ID required for the Audio Quiz Generator.

## Setting Tokens

Open the `audio_rec.py` file and add the following in line 16 :

```
 API_KEY = <yout-token>
```

## Executing the App

After installing dependencies and setting secrets, execute the Exam Generator app by running:

```
streamlit run audio_rec.py
```

The Quiz Generator app should now be accessible in your web browser at `http://localhost:8501`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.







