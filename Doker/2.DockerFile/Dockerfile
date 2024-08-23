FROM jupyter/base-notebook:latest

WORKDIR /home/jovyan/work

COPY . /home/jovyan/work

EXPOSE 8889

RUN pip install pandas matplotlib

CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--port=8889","--no-browser"]
