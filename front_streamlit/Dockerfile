FROM python:3.9

WORKDIR /opt/car_evaluation_streamlit

ADD ./front_streamlit /opt/car_evaluation_streamlit
RUN pip install --upgrade pip
RUN pip install -r /opt/car_evaluation_streamlit/requirements.txt

EXPOSE 8501

CMD ["streamlit", "run", "app.py"]