# WhatsApp Chat Analysis Project
The source of the messages is a whatsapp group of former high school classmates from my native country (Argentina). The group was very active and I decided to analyze it because of the trust and curiosity of all the members about this analysis.
The group was over 3 years old at the time of this project and accumulated 39972 messages. Finally I decided to focus my analysis on the messages of 2023 (9770) which was a very active year, especially because of the presidential elections and the World Cup.

## Overview
This project involves the analysis of WhatsApp chat data to extract meaningful insights and perform sentiment analysis on messages and emojis. The project is divided into multiple Jupyter Notebooks, each focusing on different aspects of the analysis:

1. **ETL (Extract, Transform, Load)**
2. **Message Sentiment Analysis**
3. **Emoji Sentiment Analysis**
4. **Exploratory Data Analysis (EDA)**

## Project Structure

The project consists of the following Jupyter Notebooks:

1. `whatsapp_1-3_ETL_Extract_Transform_Load.ipynb` - This notebook handles the extraction, transformation, and loading of WhatsApp chat data.
2. `whatsapp_41_Msg_Sentiment_Analysis.ipynb` - This notebook focuses on sentiment analysis of the text messages.
3. `whatsapp_42_emoji_Sentiment_Analysis.ipynb` - This notebook performs sentiment analysis on emojis used in the chat data.
5. `whatsapp_5_EDA_Exploratory_Analysis.ipynb` - This notebook performs exploratory data analysis on the chat data to uncover patterns and insights.

## Setup

### Prerequisites

Ensure you have the following installed:

- Python 3.7 or higher
- Jupyter Notebook
- Necessary Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - plotly
  - bertopic
  - umap-learn
  - sklearn
  - re
  - datetime

<picture>
 <source media="(prefers-color-scheme: dark)" srcset="YOUR-DARKMODE-IMAGE">
 <source media="(prefers-color-scheme: light)" srcset="YOUR-LIGHTMODE-IMAGE">
 <img alt="YOUR-ALT-TEXT" src="YOUR-DEFAULT-IMAGE">
</picture>


### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv newenv
   source newenv/Scripts/activate  # On Windows
   # source newenv/bin/activate   # On macOS/Linux
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Add the virtual environment to Jupyter as a kernel:**
   ```bash
   python -m ipykernel install --user --name=newenv --display-name "Python (newenv)"
   ```

## Notebook Details

### 1. ETL (Extract, Transform, Load)

This notebook covers:
- Extracting raw WhatsApp chat data.
- Cleaning and transforming the data into a usable format.
- Loading the transformed data for further analysis.

### 2. Exploratory Data Analysis (EDA)

This notebook covers:
- Descriptive statistics of the chat data.
- Visualization of chat patterns, such as message frequency, word usage, and sender activity.

### 3. Message Sentiment Analysis

This notebook covers:
- Sentiment analysis of text messages using machine learning techniques.
- Visualization of sentiment trends over time.

### 4. Emoji Sentiment Analysis

This notebook covers:
- Sentiment analysis of emojis used in the chats.
- Analysis of how emojis correlate with the sentiment of messages.


## Conclusions
As said, the source of the messages is a whatsapp group of former high school classmates from my native country (Argentina). 
It's very active and I decided to analyze it because of the trust and curiosity of all the members about this analysis.
The group was over 3 years old at the time of this project and accumulated 39972 messages, 
but I decided to focus my analysis on the messages of 2023 (9770) which was a very active year, especially because of the presidential elections and the World Cup.

### Chat with emoji
As part of the analysis I included emojis, because much of the communication is affected by these elements.
As you can see, the use of emojis is 10% of the total communication. 
The rest is just text.

![newplot (41)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/ac5683fe-fae3-4e3f-930d-363136ca651a)

### Ranking de emojis
I thought it would be interesting to dwell on this subject. First I made a ranking of emojis by user. 
It can be seen that there are users that make a more intensive use of emojis in comparison with others. 
Here you can see that Chongui, Fede and Juan appear in the first positions. Later we will see that they are the most interactive. 
It makes sense...

![image](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/39333f84-6597-4baf-96d5-0a70c1421b7c)

Another look, lets us see which emojis are the most used emojis
It looks like you've got a fun list of popular emojis and their usage counts! 
Emojis add so much flavor to our digital conversations, don't they?
Here's the breakdown:

1. 😂: 503
2. 🤣: 277
3. 🏻: 221
4. 😅: 169
5. 👏: 149
6. 🤷: 89
7. 🤦: 80
8. 💪: 65
9. 🐔: 54
10. 🤔: 50
11. 🍾: 46
12. 🤪: 42
13. 🎂: 42
14. ✌: 42
15. 🎉: 39

### Sentiment polarity 
Now entering the polarity analysis, it can be seen that the use of emojis is more associated to messages with positive connotations. 
When the messages do not have emojis, the negative content of the messages is significantly higher (42%). 
While when emojis are used, the negative messages drop to 25%.

![newplot (42)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/b92f58e7-af15-48a2-9655-defb096a7046)

### Charateristic of messages
Another interesting feature, you can see in the word count per message, 
you can see that most of the messages are less than 100 characters. 
At the top of the outliers are Delca, with a message that exceeded 400 characters...

![newplot (43)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/a79b114a-8656-41eb-9406-e470ada7d252)

### Interventions throughout the year
it can be seen how the number of interventions increased in September,
with the busiest day being August 14, 2023. 
Can you guess? what was it about? the world cup... 
Actually it was the presidential elections..

![newplot (44)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/cdb10298-3e42-4e17-bf68-46b9ef9f411e)

You can also see the increase in the intervention of the different members

![newplot (45)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/de4bd863-17af-4e15-aee2-47c14919c220)

### Interaction during day/weekdays
You can see that the busiest time is Tuesday afternoon and Wednesday afternoon
![newplot (47)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/da3ef093-436e-45c2-8e5b-86c372cd51b5)
Here you can see the participation of the members during the days of the week
![newplot (48)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/264e7a37-f7ff-459a-aae0-9b53d2c4a6aa)

### Interaccion between members
According to the analysis Fede and Chongui were the most interactive members.
Do you remember those names?
I mentioned them to you at the beginning, when we talked about the use of emojis, remember...
The analysis is very faithful to reality, these two good friends are the most prolific and are always at the head of all the debates... 
Together with Juan, they do not miss any opportunity to give their opinion and raise the temperature of the debates. ..
![newplot (49)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/25f1fb1b-d1cd-4a1d-a071-aab8bca092ee)
Here you have another approach, both analyzes are based on the basis that each message is a response to the previous message. 
It has a margin of error, which is generated when someone makes a new comment, completely disconnected from the previous one, 
or when someone responds to a message that is not the previous one... 
but after reviewing it, we confirmed that the vast majority of messages respond to the previous immediate message...
![newplot (50)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/eadf3fba-4cdb-48b5-9280-57da90e3aa0e)

### topics
With the help of multilingual Bertopic I carried out this analysis that allows us to predict the most common topics.
Personally I'm not surprised that birthday greetings come first...
![newplot (52)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/54c5db32-25b2-4085-b4a5-a42a6afb6845)

### Final conclusion
After analyzing the WhatsApp group chat, it can be concluded that the group:
1. It is a space where members laugh a lot and show appreciation for each other.
2. However, the predominant sentiment is negative
3. Politics seems to be the most frequent topic (futbol appears in the background).

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to all the contributors and the open-source community for their valuable work.
- Special thanks to the authors of the libraries used in this project.

---

This README provides a clear and structured overview of your project, including setup instructions, usage details, and descriptions of each notebook's purpose. Make sure to replace placeholder text like `<repository-url>` and `<repository-directory>` with actual information relevant to your project.
