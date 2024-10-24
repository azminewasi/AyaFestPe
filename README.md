# **AyaFestPe**
Your multi-lingual and multi-cultural festival exploration guide!

<img src="img\M.png">

<div>
<b><i>Azmine Toushik Wasi, Wahid Faisal</i></b></br>
    Cohere for AI Community, </br>
    Computational Intelligence and Operations Laboratory </br>
    <i>Both authors contributed equally</i>
</div>

---

## Project Overview
Watching videos and photos of festivals on social media, news channels, and television often makes us wonder if we could join or visit one ourselves. Festivals are a beautiful combination of culture, music, dance, art, and food. They bring people together, showcasing unique traditions and celebrations that vary from place to place. The joy of experiencing a festival firsthand is a strong desire many of us share.

However, cultural and language differences can pose challenges when preparing for these festivals. Different places have their own customs, traditions, and languages, which can make it hard to fully understand and participate. Additionally, food preparation can be tricky, as every festival often features special dishes that may be unfamiliar or hard to make without local knowledge.

To ease your way into the festival experience, we designed this notebook where you can talk and learn about festivals in your own language, with responses that are more culturally and linguistically aligned. We use new mystery model by Cohere with multilingual retrieval-augmented generation (RAG) to help you explore and enjoy festivals from around the world.


---

*AyaFestPe* means "I'm coming to the festival" in Hindi. We chose this name because it rhymes nicely with "aya," creating a catchy and memorable title for our festival initiative.  This notebook showcases extra-ordinary multi-lingual and multi-cultural capabilities of `Aya-Expanse`.

---

[***View in Colab >>***](https://colab.research.google.com/drive/10bdU0EjZ5sB6ULHXtWMVf4WBbwfJOCuV#scrollTo=dleP-sRiNISu)


## Technical Overview
The festival exploration pipeline begins by collecting festival data from Hugging Face, which provides rich information about various celebrations. Next, we use the Mystery Model to translate this data into different languages, making it accessible to a wider audience. Afterward, we collect user queries to understand what information they are looking for. We then use retrieval-augmented generation (RAG) by embedding all the data and user queries. This allows us to rerank the results and gather relevant context for the user’s query. Finally, we combine this context with the user query to generate meaningful and informative output tailored to their needs.

<img src="img\Model.png">

---

### Cite as:
```
@techreport{wasi-wahid-ayafestpe,
  author      = "Azmine Toushik Wasi and Wahid Faisal",
  title       = "AyaFestPe : A Multi-lingual and Multi-cultural Festival Exploration Guide",
  institution = "Cohere for AI Community and Computational Intelligence and Operations Laboratory",
  year        = "2024",
  url         = "https://github.com/azminewasi/AyaFestPe"
}
```