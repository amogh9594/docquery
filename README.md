# DocQuery
DocQuery is a library and command-line tool that makes it easy to analyze semi-structured and unstructured documents (PDFs, scanned images, etc.) using large language models (LLMs). You simply point DocQuery at one or more documents and specify a question you want to ask. 

Install Package 
```
pip install docquery
```
```
!apt install tesseract-ocr
```
docquery scan allows you to ask one or more questions to a single document or directory of files. DocQuery can also be used as a library. It contains two basic abstractions: (1) a DocumentQuestionAnswering pipeline that makes it simple to ask questions of documents and (2) a Document abstraction that can parse various types of documents to feed into the pipeline.

DocQuery App : [Application](https://huggingface.co/spaces/impira/docquery)
Impira : [Developer Credit](https://github.com/impira/docquery)
