# Taiwan's Road Names and the Struggle Over National Identity

Taiwan's road names tell the story of struggle over national identity. In the shadow of rising cross-strait tensions, they reveal how the legacy of Chinese nationalism continues to shape public space and raise urgent questions about what it means to be Taiwanese today.
View the full project [here](https://ashley-yihui-lee.github.io/taiwan-road).

---

## 📊 Data Sources

- **Road Names Data**  
  Sourced from [Taiwan’s Post Offcie](https://www.post.gov.tw/post/internet/Postal/index.jsp?ID=207)  
  I scraped the data with Playwright. View the dataset with all cities and counties with Pinyin translation at [merged.csv]
  
- **NCCU Election Study Center**  
  Sourced from [NCCU Election Study Center](https://esc.nccu.edu.tw/PageDoc/Detail?fid=7804&id=6960) 
  Includes data on Taiwanese/Chinese identity of people in Taiwan.

---

## 🎥 Photo and Map Used

- **Presidential Office Map**  
  Source: [Snazzy Maps](https://snazzymaps.com)
  Style ("High contrast roads") created by catherine
  Edited in Adobe Illustrator

- **Taipei Road Photo**  
  Photo by Jimmy Liao on Pexels
  https://www.pexels.com/photo/motor-vehicles-on-the-street-11906766/
---

## Methodology
Methodology
To analyze how Taiwan’s street names reflect national identity, I first scraped address data from the official Taiwan Post Office website, which provides a comprehensive list of all road names across the island, organized by city and district. Using an automated script built with Playwright, I extracted the names of streets from every locality, resulting in a dataset of 45,044 entries.

Next, I processed the data to identify the most frequently occurring characters and phrases in road names—such as “中山” (Zhongshan), “中正” (Zhongzheng), and “民族” (Minzu)—which are often linked to political figures, ideologies, or places in mainland China. I counted the frequency of each unique name element and compiled a ranked list of the top 10 most common road names across Taiwan.

To make this data accessible to an international audience, I joined the results with a separate dataset published by Taiwan’s Ministry of the Interior, which includes official English translations of road names. This allowed for bilingual analysis and visualization of naming patterns.

Through this method, I traced how streets named decades ago continue to carry the legacy of Chinese nationalism—and how these naming conventions persist even as Taiwanese identity evolves.

