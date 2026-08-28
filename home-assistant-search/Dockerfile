FROM python:3-alpine

WORKDIR /HomeAssistantSearch
COPY index.html ./

EXPOSE 7666
CMD ["python3", "-m", "http.server", "7666"]