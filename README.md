# OHAE
KB 3rd Future Finance A.I. Challenge Project Repository   
Check out Presentation at [Link](https://github.com/woog2ee/OHAE/blob/main/KB%20Future%20Finance%20A.I.%20Challenge%20%EA%B8%B0%EC%88%A0%EC%84%A4%EB%AA%85%EC%84%9C%20(OHAE%ED%8C%80).pdf)

## ๐ช Teammates
- Team name: **OHAEํ**, KB์ฆ๊ถ M-able mini๊ฐ ํ์ ์คํด
- **Seunguk Yu**: School of Computer Science & Engineering in CAU   
- **Yejin Kwon**: School of Applied Statistics in CAU   
- **Minju Kim**: School of Business & Economics in CAU   

## ๐ก Prototype
Designed by [Adobe XD](https://www.adobe.com/kr/products/xd.html)

### 1. M-able mini์ ์คํด๊ฐ ๋ง๋๋ค
MZ์ธ๋๋ฅผ ํ๊ฒ์ผ๋ก kb์ฆ๊ถ์์ ๋ฐ์นญ๋ M-able mini์ **'์ค๋์ ํด์ํ๊ทธ, ์คํด'** ์๋น์ค ์ถ๊ฐ
![image](https://user-images.githubusercontent.com/80081987/132034685-32163dc5-3ab3-41b2-8253-cb12c27e871a.png)

### 2. ์ผ๋ณ ์ธ๊ธ๋์ผ๋ก ๋ง์ด ์ธ๊ธ๋ ์ข๋ชฉ์ด ๋ฌด์์ธ์ง ํ๋์
๋ค์ด๋ฒ๋ด์ค, ๋ค์๋ด์ค, ๋์์ธ์ฌ์ด๋ ์ฃผ์๊ฐค๋ฌ๋ฆฌ, ๋ค์ด๋ฒ ์ขํ ๋ฐฉ, ์ ํ๋ธ์ ์ธ๊ธ๋ ์ข๋ชฉ์ ์ผ๋ณ ์ธ๊ธ๋์ ํ๋ฒ์ ํ์ธ
![image](https://user-images.githubusercontent.com/80081987/132034702-2a4d3a87-5cdd-42c6-afe1-6cead4833829.png)

### 3. ์ข๋ชฉ์ ๋ํ ์คํด์, ์คํด์ ๋ฐ๋ฅธ ๊ฐ์ฑ๋ถ์์ ํ๋์
์ข๋ชฉ๋ณ '์ค๋์ ํด์ํ๊ทธ, ์คํด'์ ๊ทธ์ ๋ฐ๋ฅธ ์ฐ๊ด์ด๊ฐ ๋ฌด์์ด๋ฉฐ ๊ฐ์ฑ๋ถ์ ๊ฒฐ๊ณผ๊ฐ ์ด๋ป๊ฒ ๋๋์ง ํ๋ฒ์ ํ์ธ
![image](https://user-images.githubusercontent.com/80081987/132034722-42c1078f-a2de-464e-be03-2f40d85d977f.png)

## ๐ Pipeline
### 1. Data Crawling & Preprocessing
๋ค์ด๋ฒ๋ด์ค, ๋ค์๋ด์ค, ๋์์ธ์ฌ์ด๋ ์ฃผ์๊ฐค๋ฌ๋ฆฌ, ๋ค์ด๋ฒ ์ขํ ๋ฐฉ, ์ ํ๋ธ์   
์ข๋ชฉ์ด ์ธ๊ธ๋ ๊ฒ์๊ธ ๋ฐ ์์์ ์ ๋ชฉ/๋ณธ๋ฌธ/๋๊ธ์ Selenium๊ณผ BeautifulSoup์ผ๋ก ํฌ๋กค๋ง

### 2. Text Analyzing
๊ฐ ์ข๋ชฉ๋น ์ผ๋ณ ์ธ๊ธ๋ ๋ฐ ์ ์๋ ๊ธฐ๊ฐ์ ์ธ๊ธ๋ ๋ณ๋ ์ถ์ด ์๊ฐํ   
๋น๋์๋ฅผ ๊ธฐ๋ฐ์ผ๋ก ์ค๋์ ํด์ํ๊ทธ, ์คํด ์ ์  ๋ฐ ์คํด ์ฐ๊ด์ด ์ ์ 

### 3. Sentiment Analysis
์ง์  ์ป์ 10์ผ์น ๋ฐ์ดํฐ์ kb-albert๋ฅผ ์ด์ฉํ์ฌ ๊ฐ์ฑ๋ถ์ ๋ชจ๋ธ ํ์ต์ ์งํ   
์ค๋์ ํด์ํ๊ทธ, ์คํด ์ฐ๊ด์ด๊ฐ ํฌํจ๋ ํ์คํธ์ ๋ชจ๋ธ์ ์ ์ฉํด ์ฃผ์ ์ข๋ชฉ์ ์คํผ๋์ธ ๋ง์ด๋
