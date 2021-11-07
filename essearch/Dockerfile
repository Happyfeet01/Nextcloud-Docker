FROM elasticsearch:7.14.2
RUN apt install tesseract-ocr tesseract-ocr-eng tesseract-ocr-deu
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch ingest-attachment
