FROM python:alpine
RUN pip install Flask
COPY rng.py /
CMD ["sudo su"]
CMD ["python", "rng.py"]
EXPOSE 8080
