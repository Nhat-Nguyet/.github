<h1 align="center">Nhat Nguyet</h1>

<p align="center">
  <b>Open source tools for East Asian calendars and traditional knowledge, and for safer AI.</b><br>
  The engine behind <a href="https://nhatnguyet.org/en">nhatnguyet.org</a>: lunar calendars, Zi Wei Dou Shu, BaZi, the I Ching, numerology and feng shui, computed from astronomy and explained from the classics, in English, 中文 and Tiếng Việt.
</p>

<p align="center">
  <a href="https://nhatnguyet.org/en/ma-nguon-mo">Project page</a> ·
  <a href="https://nhatnguyet.org/en/ma-nguon-mo/tai-lieu">Docs</a> ·
  <a href="https://nhatnguyet.org/en/du-lieu">Open data</a> ·
  <a href="https://huggingface.co/nhatnguyet">Hugging Face</a> ·
  <a href="mailto:lienhe@nhatnguyet.org">Contact</a>
</p>

## What we publish

### [nhatnguyet-lunar-ziwei-bazi-numerology](https://github.com/Nhat-Nguyet/nhatnguyet-lunar-ziwei-bazi-numerology)

Libraries for JavaScript and Python, plus an MCP server for AI assistants.

- Lunar calendars of China, Korea, Japan, Vietnam and 7 more countries and regions, with new moons and solar terms checked against NASA and IMCCE from 1900 to 2100.
- Zi Wei Dou Shu, BaZi, the I Ching, numerology and feng shui. Where the schools disagree, you choose the school instead of getting one silent default.
- 17,291 shared test vectors, so JavaScript and Python give the same answer.
- 14 MCP tools, so a model looks up a date or casts a chart instead of guessing.

```bash
npm i @nhatnguyet/ziwei @nhatnguyet/lunar   # or: pip install nhatnguyet
```

### Open data

3.6 million charts with readings that cite the classics by book and chapter, and 33 datasets with DOIs, released under CC BY 4.0. They are on [Hugging Face](https://huggingface.co/nhatnguyet), [Zenodo](https://doi.org/10.5281/zenodo.24358013) and [du-lieu-am-lich](https://github.com/Nhat-Nguyet/du-lieu-am-lich).

### AI safety

- [guardrail-chatbot-jev](https://github.com/Nhat-Nguyet/guardrail-chatbot-jev): content safety guardrails for AI chatbots. Input, output and whole-conversation checks run from one policy file, with a compliance pack for Vietnamese law.
- [guardrail-rag-jev](https://github.com/Nhat-Nguyet/guardrail-rag-jev): guardrails for RAG. It checks documents before indexing, user queries, retrieved passages and answers, and names the legal basis of every violation.

### Product management

[product-skill-jev](https://github.com/Nhat-Nguyet/product-skill-jev): a product management co-pilot that writes the documents, keeps the process honest and leaves every decision to you.

### [nhatnguyet-widgets](https://github.com/Nhat-Nguyet/nhatnguyet-widgets)

14 free widgets that each go into a page with two lines of HTML: lunar calendar, today's date, auspicious hours, date converter, Tết countdown, Lỗ Ban ruler and more. No account or API key, in Vietnamese, English or Chinese.

## How we work

- **Sources first.** Calendar results are checked against astronomy. Readings quote the book and chapter they come from.
- **Schools stated.** When traditions differ, we name each one and let you choose.
- **Same answer everywhere.** The website, the app, the libraries and the datasets all run on one engine.

Code is MIT, data is CC BY 4.0. Issues, discussions and pull requests are welcome.

---

<p align="center">
  <b>Tiếng Việt.</b> Nhật Nguyệt là nền tảng tri thức và tra cứu về lịch pháp, Tử Vi, Bát Tự, Kinh Dịch, thần số học, phong thuỷ và văn hoá tâm linh Việt Nam. Mã nguồn, dữ liệu mở và rào chắn an toàn cho AI ở đây là chính bộ máy chạy <a href="https://nhatnguyet.org">nhatnguyet.org</a>.<br>
  <b>中文.</b> Nhat Nguyet 提供东亚历法与传统术数的开源程序库和开放数据，并发布 AI 内容安全护栏。
</p>
