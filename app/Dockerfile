FROM python:3.8

EXPOSE 5000

WORKDIR /app

COPY requirements.txt /app
RUN python -m pip install --trusted-host pypi.python.org --trusted-host files.pythonhosted.org --trusted-host pypi.org --upgrade pip

COPY app.py /app
CMD python app.py