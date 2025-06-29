# <p align="center">Knowing the Words, Missing the Meaning </p>

## ✨ Introduction  
This benchmark is designed to evaluate the cultural understanding and natural language processing capabilities of large language models based on SinoKorean words and four-character idioms, which are essential linguistic and cultural assets in Korea.  
This highlights a gap in LLMs’ understanding of Korea-specific Hanja culture and underscores the need for evaluation tools that reflect these cultural distinctions.


## 📑 Dataset Description  
Reflecting the official question types of the Korean Hanja Proficiency Test, the benchmark consists of: four-character idioms, synonyms, antonyms, homophones, and Hanja list.


## 📚 Construction  
The benchmark dataset for this study was constructed based on the official question types used in the [Korean Hanja Proficiency Test](https://www.hanja.re.kr/), a government-certified examination that assesses proficiency in Hanja.  
We focused on Grade 1 to Grade 6, as these levels are widely taken by test candidates and cover the common-use Hanja shared across multiple testing institutions.

The dataset includes:

- **Four-character idioms**: Each entry includes the idiom, its constituent characters, and the Korean definition.  
- **Synonyms & Homophones**: Each entry presents a two-syllable Sino-Korean word, its Hanja form, and Korean meaning.  
- **Antonyms**: Each entry pairs a base term with its antonym, along with the Korean definition of the antonym.  

Each question type contains **200 samples**, with balanced distribution across all categories.  
Additionally, a supplementary dataset of **3,781 individual Hanja entries** was created to support the generation of answer choices, including each character’s form, pronunciation, and Korean meaning.


## 📊 Structure  
The dataset is organized as follows:
<pre><code> Knowing the words Missing the Meaning
  └── Dataset_csv
      ├── Four-character idioms
      ├── Synonyms
      ├── Antonyms
      ├── Homophones
      └── Hanja List </code></pre>


## 📧 Contact  
For any questions, feel free to contact me: **es133lolo@knu.ac.kr**

