# arxivData

This project is aim to help researchers in field of data analysis, machine learning and deep learning. arxivData is file contains all the name of paper, authors, summary, publish data, title and pdf link for download.

You can use this tool to search top papers from the field, You can also search for papers based on the topic you need. It makes easy to search for specific paper instead of just goto scholar and search random papers. 

Strucutre of the data:
```
{
        "author": "[{'name': 'X'}, {'name': 'Y'}]",
        "day": x,
        "id": "xxx.xxxxxx",
        "link": "[{'rel': 'alternate', 'href': 'http://arxiv.org/abs/xxxx.xxxxx', 'type': 'text/html'}, {'rel': 'related', 'href': 'http://arxiv.org/pdf/xxxx.xxxxxx', 'type': 'application/pdf', 'title': 'pdf'}]",
        "month": x,
        "summary": "etc......",
        "tag": "[{'term': 'cs.AI', 'scheme': 'http://arxiv.org/schemas/atom', 'label': None}, {'term': 'cs.CL', 'scheme': 'http://arxiv.org/schemas/atom', 'label': None}, {'term': 'cs.CV', 'scheme': 'http://arxiv.org/schemas/atom', 'label': None}, {'term': 'cs.NE', 'scheme': 'http://arxiv.org/schemas/atom', 'label': None}, {'term': 'stat.ML', 'scheme': 'http://arxiv.org/schemas/atom', 'label': None}]",
        "title": "XXXX...",
        "year": 2018
    }
    ```
This will be avilable for both offline and online use. It is avilable right now as offline. You can download the library and search it. 

If you have any suggetion please let us know.

Name: Neel Shah
Email: neelknightme@gmail.com
website: https://neelshah18.github.io/
