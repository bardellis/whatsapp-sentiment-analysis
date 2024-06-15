### Hi there



# WhatsApp Chat Analysis Project

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

## Usage

### Running the Notebooks

1. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. **Open and run the notebooks in the following order:**
   - `whatsapp_1-3_ETL_Extract_Transform_Load.ipynb`
   - `whatsapp_5_EDA_Exploratory_Analysis.ipynb`
   - `whatsapp_41_Msg_Sentiment_Analysis.ipynb`
   - `whatsapp_42_emoji_Sentiment_Analysis.ipynb`

### Notebook Details

#### 1. ETL (Extract, Transform, Load)

This notebook covers:
- Extracting raw WhatsApp chat data.
- Cleaning and transforming the data into a usable format.
- Loading the transformed data for further analysis.

#### 2. Exploratory Data Analysis (EDA)

This notebook covers:
- Descriptive statistics of the chat data.
- Visualization of chat patterns, such as message frequency, word usage, and sender activity.

#### 3. Message Sentiment Analysis

This notebook covers:
- Sentiment analysis of text messages using machine learning techniques.
- Visualization of sentiment trends over time.

#### 4. Emoji Sentiment Analysis

This notebook covers:
- Sentiment analysis of emojis used in the chats.
- Analysis of how emojis correlate with the sentiment of messages.


## Conclusions

## Chat with/without emoji
![newplot (41)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/ac5683fe-fae3-4e3f-930d-363136ca651a)

## Ranking de emojis
It looks like you've got a fun list of popular emojis and their usage counts! Here's the breakdown:

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

Emojis add so much flavor to our digital conversations, don't they? 😄 If you need any more information or have other questions, feel free to ask!

## negative/positive/neutral
![newplot (42)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/b92f58e7-af15-48a2-9655-defb096a7046)

## charateristic of messages (words p/chat)
![newplot (43)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/a79b114a-8656-41eb-9406-e470ada7d252)

# interventions overtime
se puede ver como se incrementó la intervecion en septiembre
![newplot (43)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/df9b1ffa-2d60-431f-aa50-a4e6312a46a7)

aca se puede ver el incremento en miembros individuales
![newplot (45)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/de4bd863-17af-4e15-aee2-47c14919c220)

![newplot (46)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/0c4456e5-b3b7-4a80-b202-0a5e07c62ffc)

## time of the day
se puede ver que el momento de mas actividad es el martes por la tarde y el miercoles durante la tarde
![newplot (47)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/da3ef093-436e-45c2-8e5b-86c372cd51b5)

aca se puede ver la participacion de los miembros durante los dias de la semana
![newplot (48)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/264e7a37-f7ff-459a-aae0-9b53d2c4a6aa)

## interaccion entre miembros
According to the analysis Fede and Chongui were the most interactive members
![image](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/02317ae8-7718-490d-9580-fb17a2087beb)

![newplot (49)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/25f1fb1b-d1cd-4a1d-a071-aab8bca092ee)

![newplot (50)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/eadf3fba-4cdb-48b5-9280-57da90e3aa0e)

## temas

![newplot (52)](https://github.com/bardellis/whatsapp-sentiment-analysis/assets/105069472/54c5db32-25b2-4085-b4a5-a42a6afb6845)


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
