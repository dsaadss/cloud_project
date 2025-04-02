https://www.youtube.com/watch?v=-DoyrhN_bxw
![image](https://github.com/user-attachments/assets/29887cb1-3724-42d5-97be-73555120816f)


![image](https://github.com/user-attachments/assets/5ff3eca3-0057-4c4a-afe5-09a46f0b87b5)

![image](https://github.com/user-attachments/assets/512261cb-0e6a-4d62-b780-aba9edc9eb81)

# 🦎 Project Salamandra

**Project Salamandra** is an interactive Python-based analysis tool for visualizing and understanding student activity logs in educational environments. Built in Google Colab and powered by Firebase, this tool transforms raw JSON data into intuitive, interactive dashboards.

## 🔧 Features

- 📊 **Tab & Document Analysis**: Track and compare time spent by users on various tabs and documents.
- ⏱️ **Activity Timelines**: Visualize when documents were opened/closed by each user.
- 📈 **User Behavior Insights**: Identify common user actions and trends.
- 🧠 **Keyword Matching & Indexing**: Analyze and compare word frequency in logs vs external documentation (e.g., Onshape glossary).
- 🤖 **Basic Chatbot Interface**: Query insights using a simple natural language interface.

## 🧪 Technologies Used

- **Languages**: Python
- **Libraries**: 
  - `pandas`, `matplotlib`, `ipywidgets`
  - `fuzzywuzzy`, `nltk`, `BeautifulSoup`
- **Platform**: Google Colab
- **Backend**: Firebase Realtime Database

## 🚀 How to Use

1. Upload a JSON file or connect to the Firebase DB.
2. Use the interactive UI to explore different visualizations.
3. Filter data by user, document, or date.
4. Click buttons to switch between views: average time, trends, distributions, and more.

## 📂 Project Structure

- `main()` — launches the main UI with options to load data.
- Analysis functions like:
  - `display_user_tab_analysis`
  - `display_document_activity_analysis`
  - `display_common_actions_and_user_activity`
  - etc.
- Keyword comparison using scraped glossary from Onshape.

## 📝 License

MIT License — feel free to use and adapt!

## 🙋‍♂️ Author

Developed by a passionate software engineering student exploring data, interaction, and visualization in education tech.

