FROM python:3

COPY requirements.txt ./

RUN pip install -r requirements.txt
#RUN pip install git+https://github.com/mjenczmyk/Packt-Publishing-Free-Learning.git@downloader

COPY . .

CMD [ "python", "script/spider.py", "-c", "config/prod.cfg", "-u", "googledrive", "-s", "firebase", "-n", "gmail" ]
