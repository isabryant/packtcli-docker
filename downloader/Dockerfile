FROM python:3

COPY requirements.txt ./

#RUN pip install --no-cache-dir -r requirements.txt
RUN pip install git+https://github.com/mjenczmyk/Packt-Publishing-Free-Learning.git@downloader

COPY . .

CMD [ "packt-cli", "-sgd" ]
