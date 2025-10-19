# Capstone-Project---News-Stance-and-Bias-Detector
### Description :
This project collects recent news articles related to a chosen topic (e.g., “Trump Tariff”), then uses IBM Granite Instruct, a large language model, to automatically analyze each article’s stance and bias. The final output is a structured dataset summarizing how different media sources portray the topic.
### Workflow :
1. The code uses NewsAPI to search for the latest and most popular articles about a chosen topic, such as “Trump Tariff”.
2. Articles that are too short or have missing content are removed to make sure the analysis is accurate.
3. The text of each article is sent to the IBM Granite Instruct AI model. The AI reads the article and determines: whether the article is Pro, Against, or Neutral about the topic (stance), and whether the tone is Objective, Emotional, Partisan, or Mixed (bias).
4. The final results are shown in a table with each article’s stance, bias, and a short explanation of why it was classified that way.
